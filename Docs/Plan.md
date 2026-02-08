# Plan

## Week 1 Goal
- 

### Week 1 Tickets
- [■] GitHub repo 생성 + 초기 커밋
- [■] Docs 템플릿 파일 생성(Scope/Wireframes/Plan/Architecture/API/Devlog)
- [■] Unreal 프로젝트 생성
- [□] Main 씬 저장 및 기본 오브젝트 배치

## Week 2 Goal
- 

### Week 2 Tickets
- [□] player 이동 구현 
- [□] Main scene 방 구현
- [□] 
- [□] 

## Week 3 Goal

- UE 프로젝트 생성 + C++ 빌드 성공 + 기본 이동이 된다.

### Week 3 Tickets

- [□] UE5 설치/프로젝트 생성(Third Person or Blank)
- [□] C++ 클래스 추가(컴파일 성공) + Git 레포 세팅
- [□] 이동/회전 입력 연결(WASD/마우스)
- [□] 간단 카메라(3인칭/탑다운 중 택1) 고정

## Week 4 Goal

- 멀티 기본: Listen Server로 2명 접속/동기화가 된다.

### Week 4 Tickets

- [□] Online Subsystem(로컬/Null) 기반 세션 생성/참가
- [□] 2클라 테스트(PIE 멀티)로 접속 확인
- [□] 캐릭터 이동/회전 Replication 확인
- [□] 간단 로비 맵/게임 맵 분리

## Week 5 Goal

- 로비 → 매치 시작 → 결과로 돌아오는 ‘게임 루프’가 생긴다.

### Week 5 Tickets

- [□] GameMode/GameState/PlayerState 흐름 정리
- [□] Ready 시스템(Ready 2명 되면 시작)
- [□] 매치 타이머 + 종료 조건(시간 끝)
- [□] 결과 화면(승패/점수) + 로비 복귀

## Week 6 Goal

- 구스구스 느낌” 핵심 상호작용 1개를 멀티로 구현한다.

### Week 6 Tickets

- [□] 상호작용 인터페이스(E) + 라인트레이스
- [□] 오브젝트 상호작용(버튼/문/미션 오브젝트 1종)
- [□] 상호작용 결과 Replication 처리
- [□] UI 피드백(간단 텍스트/아이콘)

## Week 7 Goal

- 역할(또는 팀) 개념 1개 + 승리 조건이 생긴다.

### Week 7 Tickets

- [□] 역할/팀 배정(PlayerState)
- [□] 승리 조건 1개(예: 미션 n개 완료 or 특정 역할 제거)
- [□] 승리 판정 서버 권한 처리
- [□] 결과 화면에 역할/승리 표시

## Week 8 Goal

- 맵/동선이 “한 판” 돌 수 있을 정도로 갖춰진다.

### Week 8 Tickets

- [□] 작은 맵 1개(방 4~6개, 연결 복도)
- [□] 스폰 포인트/리스폰 규칙(필요 시)
- [□] 미션 오브젝트 2~3개 배치
- [□] 최소 사운드/이펙트(상호작용)

## Week 9 Goal

 - 네트워크 안정화(지연/권한/치트 방지 기초)와 버그픽스를 한다.

### Week 9 Tickets

- [□] RPC/RepNotify 정리(서버 권한 우선)
- [□] 상태 꼬임(Ready/Start/End) 버그 수정
- [□] 접속/재접속 시 상태 초기화 처리
- [□] 로그/디버그 커맨드 최소 추가

## Week 10 Goal

 - UI/UX를 정리해서 “누가 봐도 플레이 가능한” 수준으로 만든다.

### Week 10 Tickets

- [□] 로비 UI(방 참가/나가기/Ready)
- [□] 인게임 UI(타이머/목표/상호작용 안내)
- [□] 결과 UI(승패/점수/다시하기)
- [□] 키바인딩/조작 안내 정리