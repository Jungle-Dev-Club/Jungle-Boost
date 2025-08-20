# Computer Hardware

이 섹션은 크래프톤 정글 8기 컴퓨터 하드웨어 소모임  
[C.H.I.P (Computer Hardware Industry Perspective, 칩스)](https://github.com/Computer-Hardware-Industry-Perspective) 에서 공부한 내용을 기반으로 확장하여 정리한 자료입니다.  

현재 정리 중인 자료이며, 양질의 내용을 모으고 체계적으로 다듬는 과정에 있습니다.  
업데이트가 늦어질 수 있는 점 양해 부탁드립니다.  

소프트웨어는 하드웨어 위에서 동작합니다.  
따라서 CPU, 메모리, 저장장치, GPU 같은 주요 구성 요소와 그 동작 원리를 이해하면,  
코드 실행 과정과 성능 특성을 더 정확히 파악할 수 있습니다.  
또한 시스템 성능 분석, 최적화, 장애 원인 파악 같은 실무 문제 해결에도 도움이 됩니다.  

---

## 디렉토리 구조

```

Computer Hardware/
│
├── CPU/
│   ├── instruction\_set.md        # ISA, RISC vs CISC, 파이프라이닝
│   ├── multicore.md              # 멀티코어, 병렬처리, 캐시 일관성
│   ├── cache\_memory.md           # 캐시 계층 구조, 캐시 미스/히트
│   └── cpu\_trends.md             # 최신 CPU 아키텍처 동향
│
├── Memory/
│   ├── memory\_hierarchy.md       # 레지스터 → 캐시 → RAM → Disk
│   ├── virtual\_memory.md         # 가상 메모리, 페이징, 스와핑
│   └── memory\_trends.md          # DDR, HBM, 차세대 메모리
│
├── Storage/
│   ├── hdd\_vs\_ssd.md             # HDD vs SSD 구조와 차이
│   ├── file\_system.md            # 파일시스템 개념
│   └── storage\_trends.md         # NVMe, ZNS, 스토리지 기술 동향
│
├── GPU/
│   ├── gpu\_architecture.md       # GPU 구조, CUDA Core, SM
│   ├── gpgpu.md                  # 일반 연산에서의 GPU 활용 (AI/병렬처리)
│   └── gpu\_trends.md             # DLSS, Ray Tracing, 최신 GPU 기술
│
├── Semiconductor/
│   ├── semiconductor\_process.md  # 반도체 제조 공정 개요 (포토리소그래피 등)
│   ├── fabless\_foundry.md        # 반도체 산업 구조 (팹리스, 파운드리, IDM)
│   └── industry\_trends.md        # 산업 동향, 주요 기업과 기술 로드맵
│
└── Overview/
├── why\_hardware\_matters.md   # 하드웨어 학습의 필요성 정리
├── study\_path.md             # 학습 순서와 방향 제안
└── references.md             # 참고 자료 (책, 블로그, 강의)

```

---

이 자료는 칩스에서의 학습을 토대로 깊이를 더해 확장하고 있습니다.  

틀린 부분이나 보강할 내용이 있다면 언제든 기여해주세요.  
