<div align="center">

<p>
  <a href="https://github.com/maya-thorne"><img src="../assets/hero_ko.svg" alt="Maya Thorne — Speed · Scale · Security — Linux Kernel &amp; Low-Level Concurrency" width="76%" /></a>
  <a href="https://github.com/maya-thorne"><img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" /></a>
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

<!-- 빠른 탐색 내비게이션 바 -->
<div align="center">

<p align="center">
  <a href="#about-engineering-ethos"><b>⚡ 소개</b></a> &nbsp;•&nbsp;
  <a href="#core-systems-architecture"><b>🚀 13개 리포지토리 쇼케이스</b></a> &nbsp;•&nbsp;
  <a href="#featured-capabilities"><b>⚙️ 핵심 역량</b></a> &nbsp;•&nbsp;
  <a href="#technology-stack"><b>💻 기술 스택</b></a> &nbsp;•&nbsp;
  <a href="#explore-projects"><b>🗺️ 로드맵</b></a> &nbsp;•&nbsp;
  <a href="#architecture-dashboard"><b>📊 메트릭</b></a> &nbsp;•&nbsp;
  <a href="#repository-structure"><b>📂 저장소 구조</b></a>
</p>

</div>

---

<span id="about-engineering-ethos"></span>
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

<span id="core-systems-architecture"></span>
<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 핵심 시스템 및 인프라 아키텍처</h2></summary>

<br />

고성능 분산 런타임, 커널 바이패스 네트워크 스택, 그리고 5대 연구 도메인 전반에 걸친 암호학적 프라이버시 검증 인프라 토폴로지 엔진:

### ⚡ 저수준 시스템 및 커널 프리미티브

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/ring-io">
          <img src="../assets/projects/ring-io-banner.svg" alt="ring-io banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/ring-io">⚡ ring-io</a></h4>
      <p><em>리눅스 io_uring 기반 초고성능·제로 오버헤드 비동기 I/O 런타임 엔진 (C23 표준).</em></p>
      <p>
        <a href="https://github.com/maya-thorne/ring-io"><img src="https://img.shields.io/badge/Standard-C23-10b981.svg" alt="Standard: C23" /></a>
        <a href="https://github.com/maya-thorne/ring-io"><img src="https://img.shields.io/badge/Throughput-2.85_Mops%2Fsec-38bdf8.svg" alt="Throughput: 2.85 Mops/sec" /></a>
        <a href="https://github.com/maya-thorne/ring-io"><img src="https://img.shields.io/badge/Kernel-io__uring_SQPOLL-f43f5e.svg" alt="Kernel: io_uring SQPOLL" /></a>
      </p>
      <ul>
        <li>🌀 <strong>시스템 콜 제로 링 큐</strong>: epoll/kqueue 오버헤드를 배제한 락프리 SQ/CQ 링 버퍼 기반 유저스페이스 직접 매핑</li>
        <li>⚡ <strong>커널 폴링 엔진</strong>: SQPOLL 전용 스레드 기반 2.85 Mops/sec 배치 일괄 수확 및 초저지연 I/O 처리</li>
        <li>🔒 <strong>결정론적 메모리 모델</strong>: 순수 C23 표준, CPU 캐시 정렬 데이터 구조 및 무할당(Zero-Allocation) 런타임</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/github-org-map">
          <img src="../assets/projects/github-org-map-banner.svg" alt="github-org-map banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/github-org-map">🗺️ github-org-map</a></h4>
      <p><em>리눅스 커널 연구 및 동시성 런타임 저장소의 솔트 SHA-256 프라이버시 해싱 기반 일일 자동화 토폴로지 매핑 엔진.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-license.svg" alt="Runtime: Linux & POSIX" /></a>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-actions.svg" alt="Engine: eBPF & GitOps" /></a>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-privacy.svg" alt="Privacy: Salted SHA-256" /></a>
      </p>
      <ul>
        <li>🔄 <strong>지속적 토폴로지 카토그래피</strong>: 일일 GitHub Actions 워크플로 기반 커널 연구 및 분산 시스템 저장소 자동 매핑</li>
        <li>🛡️ <strong>단방향 해시 마스킹</strong>: 비공개 커널 익스플로잇 랩을 솔트 SHA-256으로 기밀 보호하면서 계보 보존</li>
        <li>📊 <strong>순수 벡터 텔레메트리</strong>: 의존성 0%의 네이티브 2D SVG 좌표 매핑 및 프레임 정밀 타임라인 애니메이션 생성</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/github-org-map-private">
          <img src="../assets/projects/github-org-map-private-banner.svg" alt="github-org-map-private banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/github-org-map-private">🔒 github-org-map-private</a></h4>
      <p><em>저수준 커널 모듈, 익스플로잇 방어 분석 및 비공개 아키텍처 연구를 위한 격리형 컴패니언 텔레메트리 파이프라인.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-private.svg" alt="Security: Windows DPAPI Vault" /></a>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-telemetry.svg" alt="Audit: Invariant Assertions" /></a>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-format.svg" alt="Pipeline: Air-Gapped" /></a>
      </p>
      <ul>
        <li>🔐 <strong>하드웨어 바운드 보안 금고</strong>: Windows DPAPI 암호화 기반 마스터 시크릿 캡슐화로 하드웨어 종속 자격증명 보안 보장</li>
        <li>⚡ <strong>결정론적 불변식 검증</strong>: 역상 저항성과 무충돌 매핑을 기계적으로 증명하는 속성 기반 자동화 테스트 하네스</li>
        <li>📜 <strong>이중 그라운드 트루스 감사</strong>: 공개 마스킹 아티팩트와 내부 원본 그래프의 1:1 정합성을 지속 검증하는 감사 파이프라인</li>
      </ul>
    </td>
  </tr>
</table>

### 🔬 바이너리 리버스 엔지니어링 및 패커 분석

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics">
          <img src="../assets/projects/bat2exe-ghidra-forensics-banner.svg" alt="bat2exe-ghidra-forensics banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics">🔬 bat2exe-ghidra-forensics</a></h4>
      <p><em>Ghidra MCP PE 바이너리 역공학 (UPX/CLR/VB6 패커 분석), 8대 난독화 도구 소스 해체 및 다계층 AST 디옵퓨스케이션 엔진.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics"><img src="https://img.shields.io/badge/Ghidra_MCP-PE32_Binary_RE-f43f5e.svg" alt="Ghidra MCP RE" /></a>
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics"><img src="https://img.shields.io/badge/Source_Teardown-8_Core_Tools-f59e0b.svg" alt="8 Tools Dissected" /></a>
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics"><img src="https://img.shields.io/badge/Engine-Python_AST-38bdf8.svg" alt="Python AST Engine" /></a>
      </p>
      <ul>
        <li>🔬 <strong>Ghidra MCP PE 디스어셈블리</strong>: bat2exe_12.exe (UPX), example.exe (.NET CLR), BEDeCode.exe (VB6) 심층 바이너리 분해 및 제어 흐름 분석</li>
        <li>🛠️ <strong>8대 핵심 도구 원본 해체</strong>: BatCloak 폴리글랏, Somalifuscator, 0xidiz3r, Exorcism API 후킹, Bat2Exe 컴파일러 전수 코드 분석</li>
        <li>⚡ <strong>다계층 AST 디옵퓨스케이터</strong>: 6패스 정적 축소 엔진(src/deobfuscator_engine.py) 및 엔터프라이즈 Sigma/YARA 탐지 룰셋</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/dotnet-packer-forensics">
          <img src="../assets/projects/dotnet-packer-forensics-banner.svg" alt="dotnet-packer-forensics banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/dotnet-packer-forensics">🔬 dotnet-packer-forensics</a></h4>
      <p><em>상용 .NET 프로텍터를 위한 무실행 정적 포렌식 언패커, CLR 메타데이터 분석, PE 오버레이 카빙 및 듀얼 XOR 연구 아카이브.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/dotnet-packer-forensics"><img src="https://img.shields.io/badge/Engine-Zero--Dependency_Python-10b981.svg" alt="Engine: Python Zero-Dep" /></a>
        <a href="https://github.com/maya-thorne/dotnet-packer-forensics"><img src="https://img.shields.io/badge/Forensics-xorPacker_PE_Overlay-0ea5e9.svg" alt="Forensics: xorPacker PE" /></a>
        <a href="https://github.com/maya-thorne/dotnet-packer-forensics"><img src="https://img.shields.io/badge/Signatures-8_Major_Packers-f59e0b.svg" alt="Signatures: 8 Major Packers" /></a>
      </p>
      <ul>
        <li>📑 <strong>PE 오버레이 정적 카빙</strong>: PE 물리 섹션 경계를 초과하여 은닉된 페이로드를 의존성 없이 탐지하고 적출하는 순수 Python 엔진</li>
        <li>🔑 <strong>듀얼 XOR 자동 복호화</strong>: xorPacker / xorStub 암호화 컨테이너의 키 자동 탐색 및 복호화 페이로드 복원</li>
        <li>🔍 <strong>CLR 메타데이터 지문 분석</strong>: ConfuserEx, .NET Reactor, Babel, Eazfuscator, ArmDot 등 8대 프로텍터 무실행 핑거프린팅</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/batch-deobfuscator-re">
          <img src="../assets/projects/batch-deobfuscator-re-banner.svg" alt="batch-deobfuscator-re banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/batch-deobfuscator-re">🔬 batch-deobfuscator-re</a></h4>
      <p><em>다계층 배치 디옵퓨스케이터 엔진, Ghidra PE 언패커 포렌식(UPX/LZMA/XOR 오버레이) 및 48+ 오픈소스 레퍼런스 아카이브.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/batch-deobfuscator-re"><img src="https://img.shields.io/badge/Ghidra_MCP-7_PE_Binaries-0ea5e9.svg" alt="Ghidra MCP: 7 PEs Disassembled" /></a>
        <a href="https://github.com/maya-thorne/batch-deobfuscator-re"><img src="https://img.shields.io/badge/Engine-Fixed--Point_AST-10b981.svg" alt="Engine: Fixed-Point AST" /></a>
        <a href="https://github.com/maya-thorne/batch-deobfuscator-re"><img src="https://img.shields.io/badge/Packers-UPX_LZMA_XOR-a855f7.svg" alt="Forensics: UPX LZMA XOR" /></a>
      </p>
      <ul>
        <li>🌀 <strong>부동점(Fixed-Point) AST 엔진</strong>: 중첩 환경변수 슬라이싱, 탈출 캐럿, 토큰 결합을 수렴할 때까지 반복 축소하는 고속 정적 엔진</li>
        <li>🗜️ <strong>정적 PE 컨테이너 추출기</strong>: 컴파일된 래퍼 바이너리 내부에 패킹된 UPX, LZMA, XOR 오버레이 무실행 카빙 및 원본 스크립트 복원</li>
        <li>📚 <strong>플래그십 분석 및 코퍼스</strong>: 7대 대표 난독화/복원 엔진 라인별 코드 해체 및 48개 오픈소스·AI 데이터셋 인덱싱</li>
      </ul>
    </td>
  </tr>
</table>

### 🛡️ 컴파일러 및 AST 난독화 연구

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/batch-obfuscation-research">
          <img src="../assets/projects/batch-obfuscation-research-banner.svg" alt="batch-obfuscation-research banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/batch-obfuscation-research">🛡️ batch-obfuscation-research</a></h4>
      <p><em>Windows 배치 파일(cmd.exe) 난독화, 디옵퓨스케이션 및 바이너리 역공학 30년사(1990s~2026) 마스터 아카이브.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/batch-obfuscation-research"><img src="https://img.shields.io/badge/Archive-1990s--2026-10b981.svg" alt="Archive: 1990s-2026" /></a>
        <a href="https://github.com/maya-thorne/batch-obfuscation-research"><img src="https://img.shields.io/badge/Mirrors-48+_OpenSource-38bdf8.svg" alt="Mirrors: 48+ OpenSource" /></a>
        <a href="https://github.com/maya-thorne/batch-obfuscation-research"><img src="https://img.shields.io/badge/Detection-Sigma_%26_YARA-a855f7.svg" alt="Detection: Sigma & YARA" /></a>
      </p>
      <ul>
        <li>📜 <strong>30년 진화사 종합 백서</strong>: 48개 오픈소스 미러, 맨디언트/다니엘 보해넌 연구 및 허깅스페이스 AI 역공학 데이터셋 수록</li>
        <li>🧠 <strong>cmd.exe 5단계 파서 메커니즘</strong>: 환경변수 전개, 탈출 캐럿 스트리핑, 지연 확장 구문 분석 백서 완비</li>
        <li>🌐 <strong>10개 국어 로케일 지원</strong>: 다크 터미널 네온 SVG 배너 및 전용 다국어 마스터 가이드 구축</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/dotnet-obfuscation-and-ghidra-re">
          <img src="../assets/projects/dotnet-obfuscation-and-ghidra-re-banner.svg" alt="dotnet-obfuscation-and-ghidra-re banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/dotnet-obfuscation-and-ghidra-re">🛡️ dotnet-obfuscation-and-ghidra-re</a></h4>
      <p><em>블루팀 EDR/SIEM 탐지 엔지니어링, 52개 Sigma 룰, 32개 YARA 시그니처, CIL 메타데이터 포렌식 및 Ghidra 바이너리 RE 스위트.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/dotnet-obfuscation-and-ghidra-re"><img src="https://img.shields.io/badge/Sigma_Rules-52_Modular-f59e0b.svg" alt="Sigma Rules: 52 Modular" /></a>
        <a href="https://github.com/maya-thorne/dotnet-obfuscation-and-ghidra-re"><img src="https://img.shields.io/badge/YARA_Rules-32_Signatures-10b981.svg" alt="YARA Rules: 32 Signatures" /></a>
        <a href="https://github.com/maya-thorne/dotnet-obfuscation-and-ghidra-re"><img src="https://img.shields.io/badge/SIEM-Splunk_%26_Elastic-38bdf8.svg" alt="SIEM: Splunk & Elastic" /></a>
      </p>
      <ul>
        <li>🛡️ <strong>dnlib 및 안티탬퍼 포렌식</strong>: JIT 메서드 암호화, AntiDump 메모리 와이퍼, 손상된 #~ 테이블 스트림 헤더 무실행 탐지</li>
        <li>⚙️ <strong>Ghidra CIL 제어 흐름 복원</strong>: 커스텀 네이티브 가상머신 디스패치 루프 및 JIT 복호화 훅을 역추적하는 바이너리 분석 파이프라인</li>
        <li>📊 <strong>엔터프라이즈 SOC 룰셋</strong>: 상용 프로텍터 회피 기법을 완벽 커버하는 52개 모듈식 Sigma 룰 및 32개 YARA 시그니처</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/cmd-ast-deobfuscator">
          <img src="../assets/projects/cmd-ast-deobfuscator-banner.svg" alt="cmd-ast-deobfuscator banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/cmd-ast-deobfuscator">🛡️ cmd-ast-deobfuscator</a></h4>
      <p><em>Windows 명령 스크립트(cmd.exe / .bat)를 위한 다계층 추상 구문 트리(AST) 및 렉시컬 디옵퓨스케이션 엔진.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/cmd-ast-deobfuscator"><img src="https://img.shields.io/badge/Python-3.10%2B-10b981.svg" alt="Python: 3.10+" /></a>
        <a href="https://github.com/maya-thorne/cmd-ast-deobfuscator"><img src="https://img.shields.io/badge/AST-Multi--Pass_Lexer-38bdf8.svg" alt="AST: Multi-Pass Lexer" /></a>
        <a href="https://github.com/maya-thorne/cmd-ast-deobfuscator"><img src="https://img.shields.io/badge/License-MT--SRL-blue.svg" alt="License: MT-SRL" /></a>
      </p>
      <ul>
        <li>🧩 <strong>다계층 렉시컬 어휘 분석기</strong>: 중첩 탈출 캐럿(^), 환경변수 슬라이싱, 지연 확장을 모델링한 푸시다운 오토마톤 구문 분석</li>
        <li>⚡ <strong>무실행 안전 정규화기</strong>: 악성 스크립트를 동적으로 실행하지 않고 인메모리에서 안전하게 본래 페이로드 복원</li>
        <li>🛡️ <strong>포렌식 연계 파이프라인</strong>: Ghidra 바이너리 분석 결과 및 엔터프라이즈 탐지 텔레메트리 시그니처와 직통 연계</li>
      </ul>
    </td>
  </tr>
</table>

### 🔍 방어 탐지 엔지니어링 및 블루팀 포렌식

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/batch-forensics-and-ghidra-re">
          <img src="../assets/projects/batch-forensics-and-ghidra-re-banner.svg" alt="batch-forensics-and-ghidra-re banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/batch-forensics-and-ghidra-re">🛡️ batch-forensics-and-ghidra-re</a></h4>
      <p><em>블루팀 EDR/SIEM 탐지 엔지니어링, 52개 Sigma 룰, 32개 YARA 시그니처, 섀넌 엔트로피 및 캐럿 밀도 스코어링 엔진.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/batch-forensics-and-ghidra-re"><img src="https://img.shields.io/badge/Sigma_Rules-52_Modular-f59e0b.svg" alt="Sigma Rules: 52 Modular" /></a>
        <a href="https://github.com/maya-thorne/batch-forensics-and-ghidra-re"><img src="https://img.shields.io/badge/YARA_Rules-32_Signatures-10b981.svg" alt="YARA Rules: 32 Signatures" /></a>
        <a href="https://github.com/maya-thorne/batch-forensics-and-ghidra-re"><img src="https://img.shields.io/badge/SIEM-Splunk_%26_Elastic-38bdf8.svg" alt="SIEM: Splunk & Elastic" /></a>
      </p>
      <ul>
        <li>📐 <strong>섀넌 엔트로피 및 캐럿 밀도 측정기</strong>: 순수 Python 정적 분석기(src/entropy_detector.py) 기반 구분자 편향도 및 엔트로피 점수화</li>
        <li>🔍 <strong>Sysmon 및 Event 4688 커버리지</strong>: MITRE ATT&CK 방어 회피, 실행, 지속성 전술에 매핑된 52개 프로덕션 Sigma 룰</li>
        <li>🚀 <strong>방어적 5단계 파서 시뮬레이터</strong>: 인메모리 명령 언이스케이핑(src/cmd_parser_simulator.py) 기반 SOC 자동 분류</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/chromium-app-spoofing-forensics">
          <img src="../assets/projects/chromium-app-spoofing-forensics-banner.svg" alt="chromium-app-spoofing-forensics banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/chromium-app-spoofing-forensics">🛡️ chromium-app-spoofing-forensics</a></h4>
      <p><em>블루팀 EDR/SIEM 탐지 엔지니어링, 52개 Sigma 룰, 32개 YARA 시그니처, [MS-SHLLINK] 바이너리 카빙 및 윈도우 클래스 위장 감사 프레임워크.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/chromium-app-spoofing-forensics"><img src="https://img.shields.io/badge/Sigma_Rules-52_Modular-f59e0b.svg" alt="Sigma Rules: 52 Modular" /></a>
        <a href="https://github.com/maya-thorne/chromium-app-spoofing-forensics"><img src="https://img.shields.io/badge/YARA_Rules-32_Signatures-10b981.svg" alt="YARA Rules: 32 Signatures" /></a>
        <a href="https://github.com/maya-thorne/chromium-app-spoofing-forensics"><img src="https://img.shields.io/badge/LNK_Parser-MS--SHLLINK-38bdf8.svg" alt="LNK Parser: MS-SHLLINK" /></a>
      </p>
      <ul>
        <li>📑 <strong>[MS-SHLLINK] 바이너리 카빙</strong>: 순수 Python 기반 ShellLinkHeader, ExtraData 블록 파싱 및 아이콘 위치 위장 적출</li>
        <li>🔍 <strong>윈도우 클래스 계층 구조 감사</strong>: Microsoft Teams/Office 창으로 위장된 크로미움 stripped Chrome_WidgetWin_1 식별</li>
        <li>⚡ <strong>즉시 배포 SIEM 피드</strong>: 엔터프라이즈 SOC 대시보드에 즉시 투입 가능한 프로덕션 Splunk SPL 및 Elastic KQL 쿼리 완비</li>
      </ul>
    </td>
  </tr>
</table>

### 🌐 가상화, 회피 포렌식 및 프로필 아키텍처 허브

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/browser-in-the-browser-virtualization">
          <img src="../assets/projects/browser-in-the-browser-virtualization-banner.svg" alt="browser-in-the-browser-virtualization banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/browser-in-the-browser-virtualization">🌐 browser-in-the-browser-virtualization</a></h4>
      <p><em>클라이언트 사이드 DOM 가상화, 가짜 Omnibox 주소창 UI 스푸핑, 드래그 물리 엔진 및 다계층 방어 휴리스틱 연구.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/browser-in-the-browser-virtualization"><img src="https://img.shields.io/badge/DOM_Virtualization-mr.d0x_Research-8b5cf6.svg" alt="DOM Virtualization: mr.d0x" /></a>
        <a href="https://github.com/maya-thorne/browser-in-the-browser-virtualization"><img src="https://img.shields.io/badge/Heuristic_Engine-Pure--Python-38bdf8.svg" alt="Heuristic Engine: Python" /></a>
        <a href="https://github.com/maya-thorne/browser-in-the-browser-virtualization"><img src="https://img.shields.io/badge/License-MT--SRL-10b981.svg" alt="License: MT-SRL" /></a>
      </p>
      <ul>
        <li>🪟 <strong>DOM 윈도우 가상화</strong>: 가상 OS 타이틀바, mousedown/mousemove 드래그 물리 엔진, z-index 9999 스태킹 모델 심층 분석</li>
        <li>🔬 <strong>정적 및 휴리스틱 스캐너</strong>: 가짜 주소창 탐지 Python AST 분석기 및 CSP frame-ancestors 'none' 헤더 감사기</li>
        <li>🛡️ <strong>엔터프라이즈 방어 매트릭스</strong>: 프레임 버스팅 트랩, MutationObserver DOM 감시 가드, 멀티 모니터 좌표 이탈 탐지</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne">
          <img src="../assets/hero_ko.svg" alt="maya-thorne banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne">💎 maya-thorne (프로필 및 연구 허브)</a></h4>
      <p><em>GitHub 특수 프로필 저장소, 10개 국어 동적 카토그래피 아키텍처 및 자동화 텔레메트리 동기화 엔진.</em></p>
      <p>
        <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Locales-10_Languages-f59e0b.svg" alt="Locales: 10 Languages" /></a>
        <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Telemetry-Vector_SVG-38bdf8.svg" alt="Telemetry: Vector SVG" /></a>
        <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Profile-Special_Repo-10b981.svg" alt="Profile: Special Repo" /></a>
      </p>
      <ul>
        <li>🌐 <strong>10개 국어 로케일 매트릭스</strong>: 한국어, 영어, 중국어, 스페인어, 힌디어, 아랍어, 포르투갈어, 러시아어, 프랑스어, 인도네시아어 동기화</li>
        <li>📊 <strong>동적 벡터 배지 시스템</strong>: 순수 SVG 벡터 렌더링, 스트릭 통계 및 암호학적 토폴로지 매핑 통합</li>
        <li>🏛️ <strong>통합 연구 분류 체계</strong>: 12개 전문 저수준 시스템, 역공학 및 방어 탐지 엔지니어링 저장소의 유기적 연계</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">공개 저장소 둘러보기</a> ·
  <a href="https://github.com/maya-thorne/github-org-map">시스템 토폴로지 탐색하기</a>
</p>

</details>

---

<span id="featured-capabilities"></span>
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

<span id="technology-stack"></span>
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

<span id="explore-projects"></span>
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

<span id="architecture-dashboard"></span>
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

<span id="repository-structure"></span>
<details open>
<summary><h2 style="display:inline-block; margin:0;">📁 프로필 저장소 구조 및 디렉토리 맵</h2></summary>

<br />

<table width="100%">
  <thead>
    <tr>
      <th width="30%" align="left"><nobr>📁 경로 / 자산</nobr></th>
      <th width="20%" align="left"><nobr>⚙️ 분류</nobr></th>
      <th width="50%" align="left"><nobr>📝 엔지니어링 역할 및 명세</nobr></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong><code>assets/projects/</code></strong></td>
      <td>벡터 자산</td>
      <td>13개 전체 시스템 연구 저장소의 고해상도 SVG 프로젝트 배너 (XML 100% 유효)</td>
    </tr>
    <tr>
      <td><strong><code>assets/badges/</code></strong></td>
      <td>시각적 텔레메트리</td>
      <td>연구 중점, 텔레메트리 상태 및 보안 사양을 나타내는 커스텀 벡터 배지</td>
    </tr>
    <tr>
      <td><strong><code>assets/stats/</code></strong></td>
      <td>메트릭 텔레메트리</td>
      <td>실시간 아키텍처 및 기여 텔레메트리 SVG 배지</td>
    </tr>
    <tr>
      <td><strong><code>locales/</code></strong></td>
      <td>다국어 지원</td>
      <td>10개 언어 글로벌 프로필 쇼케이스 (<code>ar</code>, <code>en</code>, <code>es</code>, <code>fr</code>, <code>hi</code>, <code>id</code>, <code>ko</code>, <code>pt-BR</code>, <code>ru</code>, <code>zh-CN</code>)</td>
    </tr>
    <tr>
      <td><strong><code>avatar.svg</code></strong></td>
      <td>브랜딩 자산</td>
      <td>Maya Thorne의 기하학적 벡터 모노그램</td>
    </tr>
    <tr>
      <td><strong><code>hero.svg</code></strong></td>
      <td>브랜딩 자산</td>
      <td>반응형 와이드스크린 터미널 테마 헤더 배너</td>
    </tr>
    <tr>
      <td><strong><code>.gitignore</code></strong></td>
      <td>보안 격리 경계</td>
      <td>AI 메모리, 자격증명 및 OS 캐시 파일 유출을 원천 차단하는 제로 리크 격리 경계</td>
    </tr>
    <tr>
      <td><strong><code>LICENSE</code></strong></td>
      <td>라이선스 규약</td>
      <td>Maya Thorne Systems &amp; Security Research License (MT-SRL)</td>
    </tr>
    <tr>
      <td><strong><code>README.md</code></strong></td>
      <td>메인 진입점</td>
      <td>5대 시스템 도메인에 걸친 13개 연구 저장소를 총괄하는 GitHub 프로필 대시보드</td>
    </tr>
  </tbody>
</table>

</details>

---

## 📬 문의 및 협업

저수준 시스템 아키텍처, 리눅스 커널 내부 구조, 초고성능 동시성 프리미티브에 대해 논의를 환영합니다. (ง •̀_•́)ง

🐙 [GitHub 프로필](https://github.com/maya-thorne) · 📦 [공개 저장소](https://github.com/maya-thorne?tab=repositories) · 💬 [토론 공간](https://github.com/maya-thorne?tab=discussions) · ✉️ [이메일 보내기](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · 시스템 아키텍처 및 커널 엔지니어링 ( 💻 ˘◡˘ )</sub>
</div>
