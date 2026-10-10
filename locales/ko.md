<div align="center">

<p>
  <img src="../assets/hero_ko.svg" alt="Maya Thorne — Speed · Scale · Security — Linux Kernel &amp; Low-Level Concurrency" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction. 🚀 ( •̀ᴗ•́ )و</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <strong>🇰🇷 한국어</strong> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
  <a href="./ar.md">🇸🇦 العربية</a> · <a href="./pt-BR.md">🇧🇷 Português</a> · <a href="./ru.md">🇷🇺 Русский</a> · <a href="./fr.md">🇫🇷 Français</a> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<p>
  <a href="https://github.com/maya-thorne"><img src="../assets/badges/badge-status.svg" alt="Status" /></a>
  <a href="https://github.com/maya-thorne?tab=repositories"><img src="../assets/badges/badge-focus.svg" alt="Focus" /></a>
  <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-architecture.svg" alt="Architecture" /></a>
  <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-systems.svg" alt="Systems" /></a>
</p>

</div>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ 소개 및 엔지니어링 철학</h2></summary>

<br />

복원력 있는 저수준 소프트웨어 시스템, 리눅스 커널 모듈 및 초고성능 동시성 프리미티브를 설계합니다. 기계적 공감(Mechanical Sympathy)과 제로 오버헤드 원칙에 기반한 엔지니어링을 추구합니다:

- ⚡ **제로 비용 추상화와 기계적 공감** — CPU 캐시 계층 구조, 메모리 정렬 및 분기 예측기를 존중하는 설계. 불필요한 런타임 오버헤드를 배제한 제로 코스트 추상화 기본 적용.
- 🐧 **커널 중심 아키텍처** — 운영체제 커널을 불투명한 추상화가 아닌 1급 실행 계층으로 다룸. io_uring, eBPF 및 락프리 링 버퍼 심층 운용.
- 🛡️ **불변식 기반 무결성** — 컴파일 타임 검증 기반 안전성 강제. 엄격한 상태 머신 전이, 락프리 링 버퍼, 지속적 퍼징(Fuzzing) 검증.

<p align="center">
  <sub><em>(⌐■_■) 💻 "우리는 터미널을 신뢰한다. 결정론적으로 만들어라. 불필요한 마찰을 자동화하라."</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 주요 프로젝트 및 솔루션</h2></summary>

<br />

자율 토폴로지 매핑 및 저수준 시스템 인프라입니다. 공개 프로젝트는 직관적으로 탐색할 수 있으며, 비공개 커널 모듈과 내부 텔레메트리는 암호학적으로 마스킹되어 안전하게 보호됩니다.

### 🛠️ 주요 시스템 및 솔루션

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/github-org-map">
          <img src="../assets/projects/github-org-map-banner.svg" alt="github-org-map banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/github-org-map">🗺️ github-org-map</a></h4>
      <p><em>리눅스 커널 연구 및 동시성 런타임 저장소의 암호화 해시 마스킹 기반 일일 자동화 토폴로지 매핑 엔진.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/github-org-map/blob/main/LICENSE"><img src="../assets/badges/badge-license.svg" alt="License" /></a>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-actions.svg" alt="Actions" /></a>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-privacy.svg" alt="Privacy" /></a>
      </p>
      <ul>
        <li>🔄 <strong>자동화 파이프라인</strong>: 토큰 유출 0% 보장 일일 GitHub Actions 워크플로 기반 벡터 토폴로지 자동 동기화</li>
        <li>🛡️ <strong>프라이버시 보호</strong>: 비공개 커널 연구 모듈을 단방향 솔트 SHA-256 해시로 마스킹하여 아키텍처 계보 안전 보존</li>
        <li>📊 <strong>순수 벡터 렌더링</strong>: 외부 런타임 의존성 0%의 네이티브 SVG 좌표 매핑 및 프레임 단위 타임랩스 생성</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/github-org-map">
          <img src="../assets/projects/github-org-map.svg" alt="github-org-map telemetry" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/github-org-map-private">🔒 github-org-map-private</a></h4>
      <p><em>저수준 커널 모듈, 익스플로잇 방어 분석 및 비공개 연구를 위한 격리형 컴패니언 텔레메트리 파이프라인.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-private.svg" alt="Security" /></a>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-telemetry.svg" alt="Telemetry" /></a>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-format.svg" alt="Format" /></a>
      </p>
      <ul>
        <li>🔐 <strong>보안 금고 격리</strong>: Windows DPAPI 암호화 기반 하드웨어 바인딩 자격증명 캡슐화 및 유출 차단</li>
        <li>⚡ <strong>동시성 불변식 검증</strong>: 역상 저항성(Preimage Resistance)과 무충돌 매핑을 기계적으로 증명하는 자동화 테스트</li>
        <li>📜 <strong>이중 그라운드 트루스 감사</strong>: 공개 마스킹 아티팩트와 비공개 내부 원본 그래프의 1:1 무결성 상시 대조 검증</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">공개 저장소 둘러보기</a> ·
  <a href="https://github.com/maya-thorne/github-org-map">조직 지도 탐색하기</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚙️ 핵심 역량 및 아키텍처</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 커널 및 저수준 프리미티브</h4>
      <p><em>io_uring 기반 비동기 I/O, 커널 바이패스 네트워킹 및 실시간 관측 가능성.</em></p>
      <ul>
        <li>🌀 <strong>io_uring 및 비동기 I/O</strong>: epoll 시스템 콜 오버헤드를 배제한 고처리량 제출/완료 링 큐.</li>
        <li>⚡ <strong>커널 바이패스 및 XDP</strong>: eBPF/XDP 프로그래밍 기반 고속 패킷 필터링 및 DPDK 유저스페이스 가속.</li>
        <li>🔒 <strong>락프리 프리미티브</strong>: SPMC/MPSC 원자적 큐, 해저드 포인터 및 메모리 배리어 동기화.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 분산 시스템 및 동시성</h4>
      <p><em>CSP 스타일 동시성 파이프라인, 제로 카피 직렬화 및 메모리 안전 시스템 소프트웨어.</em></p>
      <ul>
        <li>🛠️ <strong>시스템 도구 체계</strong>: C23, 비동기 및 unsafe Rust (no_std), Zig 도구 체계.</li>
        <li>📦 <strong>제로 카피 데이터 흐름</strong>: NVMe 스토리지 패브릭 및 고대역 네트워크 기반 캐시 정렬 직렬화.</li>
        <li>🧪 <strong>불변식 검증</strong>: 상태 오토마톤 검증, 속성 기반 테스트 및 자동화 퍼징 하네스.</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">💻 기술 스택 및 도구</h2></summary>

<br />

<p><em>고성능 시스템 및 베어메탈 런타임 실행을 위한 엔지니어링 도구 모음:</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ 저수준 및 시스템</h4>
      <ul>
        <li>🔤 <strong>프로그래밍 언어</strong>: C23, Rust (Async / Unsafe / no_std), Zig, x86_64 / ARM64 어셈블리</li>
        <li>🐧 <strong>커널 런타임</strong>: 리눅스 커널 모듈, POSIX API, eBPF / XDP, io_uring</li>
        <li>🧠 <strong>메모리 및 동시성</strong>: 락프리 원자적 연산, SIMD 벡터화, NUMA 인식 할당자</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 분산 인프라 및 환경</h4>
      <ul>
        <li>⚡ <strong>네트워킹</strong>: 커널 바이패스(DPDK), 고동시성 epoll/kqueue, WebSockets, gRPC</li>
        <li>🔍 <strong>관측 가능성</strong>: bpftrace, perf, Valgrind, GDB, Prometheus 원격 측정</li>
        <li>🖥️ <strong>실행 환경</strong>: Arch Linux, Debian, Docker, LLVM/Clang 도구 모음, Neovim / Tmux</li>
      </ul>
    </td>
  </tr>
</table>

<br />

<p align="center">
  <img src="../assets/icons/tech-stack.svg" alt="Technical Stack Icons" />
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🗺️ 프로젝트 로드맵 및 탐색</h2></summary>

<br />

<p><strong>조직 지도 및 토폴로지 (Organization Map)</strong></p>

<p align="center">
  <a href="https://github.com/maya-thorne/github-org-map">
    <img src="../assets/projects/github-org-map.svg" alt="Organization map showing the maya-thorne workspace, public projects, and intentionally masked private work." width="520" />
  </a>
</p>

<p align="center">
  <sub>비공개 저장소는 솔트 기반 SHA-256 마스킹 라벨로만 안전하게 표시됩니다.</sub><br />
  <a href="https://github.com/maya-thorne/github-org-map">토폴로지 및 지도 사양 살펴보기 →</a>
</p>

<br />

<p><em>저수준 인프라 전반에 걸친 활성 로드맵 및 기술 이니셔티브:</em></p>

<ul>
  <li>🎯 <strong>현재 집중 과제</strong>: io_uring 멀티 링 폴링 벤치마크 및 커널 모듈 퍼징 하네스</li>
  <li>🚀 <strong>차기 마일스톤</strong>: NUMA 메모리 피닝 기반 락프리 SPMC 작업 훔치기(Work-Stealing) 스케줄러</li>
  <li>🔬 <strong>연구 계획</strong>: 하드웨어 오프로딩을 지원하는 eBPF 기반 네트워크 플로우 라우터</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 아키텍처 대시보드 및 지표</h2></summary>

<br />

<div align="center">
  <p>
    <a href="https://github.com/maya-thorne">
      <img src="../assets/stats/github-stats.svg" alt="Maya Thorne's GitHub Stats" />
    </a>
    <a href="https://github.com/maya-thorne">
      <img src="../assets/stats/streak-stats.svg" alt="GitHub Streak Stats" />
    </a>
  </p>
</div>

</details>

---

## 📬 문의 및 협업

저수준 시스템 아키텍처, 리눅스 커널 내부 구조, 초고성능 동시성 프리미티브에 대해 논의를 환영합니다. (ง •̀_•́)ง

🐙 [GitHub 프로필](https://github.com/maya-thorne) · 📦 [공개 저장소](https://github.com/maya-thorne?tab=repositories) · 💬 [토론 공간](https://github.com/maya-thorne?tab=discussions) · ✉️ [이메일 보내기](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · 시스템 아키텍처 및 커널 엔지니어링 ( 💻 ˘◡˘ )</sub>
</div>
