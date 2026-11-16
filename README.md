# JunSu (SuranS2)

**Java · Spring Boot 백엔드 개발 | API 구현, 오류 재현, 배포 확인**

인테리어 사업을 운영하며 고객 상담에서 정한 사양이 견적과 발주까지 정확히 이어져야 한다는 걸 배웠습니다. 개발 프로젝트에서도 화면에서 입력한 값이 API와 데이터베이스를 거쳐 어디에 쓰이는지 살피고, 수정한 뒤에는 같은 조건으로 다시 실행해 봅니다.

## 대표 프로젝트

### [AMApill](https://github.com/KOSA2025-FINAL-PROJECT-TEAM3/.github#-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%86%8C%EA%B0%9C) · 가족 복약관리 서비스

- 약봉투 사진의 OCR 결과를 등록 화면에 연결해 사용자가 확인하고 수정할 수 있게 했습니다. Spring AI로 음식 사진과 사용자의 복약·질병 정보를 함께 참고하는 식단 주의 안내를 구현했습니다.
- 발송 기록을 기준으로 미복약 알림의 반복 발행을 제어하고, 같은 조건에서 중복 표시가 사라진 것을 확인했습니다.
- Kubernetes 배포 중 Pod 로그와 노드 자원을 확인해 복제본 수와 메모리 제한을 조정했습니다. Argo CD 동기화 상태와 Pod 로그를 다시 살펴 서비스가 실행되는 것을 확인했습니다.

### [ShouxKream](https://github.com/SuranS2/ShouxKream) · 전자상거래 팀 프로젝트

- 장바구니부터 주문·결제·구매 내역까지 이어지는 기능을 개발하고, 주문 상세와 주소록을 연동했습니다.
- GitLab 이슈·MR·브랜치 규칙을 정리하고 팀 작업을 조율했습니다. Jenkins 빌드·배포 결과와 GitLab 변경 사항은 Discord 채널을 나눠 공유했습니다.

### [ZeniManager](https://github.com/SuranS2/ZeniManager) · 고용서비스 상담 지원 도구

- 현업 담당자의 실행 환경을 고려해 Electron 클라이언트를 제안하고 시연했습니다.
- React·TypeScript 상담자 등록 폼과 Supabase 저장을 연결하고, 로그인과 역할별 접근 제어를 맡았습니다.

## 사용 기술

| 분야 | 기술 |
| --- | --- |
| 백엔드·데이터 | Java, Spring Boot, Spring AI, MySQL, Redis, PostgreSQL |
| 배포·협업 | Docker, Kubernetes, Argo CD, Jenkins, GitLab |
| 웹·데스크톱 | React, TypeScript, Electron, Supabase |
| 개인 인프라 | Proxmox VE 3노드 클러스터 구성, Ansible로 LXC 초기 설정 자동화 |

## 개인 프로젝트와 오픈소스

- [bass-sound-to-muse-score](https://github.com/SuranS2/bass-sound-to-muse-score) · 음원에서 베이스 트랙을 분리하고 MuseScore에서 열 수 있는 악보와 TAB을 생성하는 Python MCP 도구입니다.
- [korea-projection PR #210](https://github.com/StopDragon/korea-projection/pull/210) · 차량 프로젝션 와이드 화면과 USB 유선 연결 변경을 제안했습니다.
