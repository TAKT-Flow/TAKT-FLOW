# TAKT FLOW for Ubuntu

TAKT FLOW combines focus timers, planning, document notes, recording, speaking
practice, and desktop widgets in one English/Korean Ubuntu workspace.

## Download and install

- [Download the latest Ubuntu release](https://github.com/TAKT-Flow/TAKT-FLOW/releases/latest)
- Supported: Ubuntu 20.04 / 22.04 / 24.04 LTS, x86-64 (amd64)

```bash
cd ~/Downloads
sudo apt install ./takt_2.0.19-1_amd64.deb
```

SHA-256:
`df7e590c3638b4bedb7b9c1aa821395636c8e70bed45b75ba65d6de6ab1448e3`

See the [installation guide](설치-매뉴얼.md) and [user guide](사용-매뉴얼.md).
This repository contains only the Ubuntu package and user documentation; app source
and Windows installers are maintained separately.

## 2.0.19 highlights

- Review a calendar's shared members from its right-click menu. Owners and
  retained co-owners can change per-member roles with inline selectors.
- Invite people as viewers, editors or administrators. Transfer primary ownership
  while retaining the former owner's full rights. Leaving as a co-owner does not
  delete the calendar or other members' content.
- Review received/sent invitation history, status filters and in-app read/response
  timestamps. This is not external email read tracking.
- Web subscriptions and agenda/document summaries now fit constrained screens,
  including at 250% scaling, with scrolling content and a reachable footer.
- Includes the calendar, input, recurring-event color and synchronization
  improvements prepared for 2.0.18. All collaborators should update to use new roles.

- Long schedule-summary cards expand to show their full text. Large agendas stay inside
  the available screen and scroll internally.
- Right-click a calendar-list entry to make that calendar, or All calendars, the first
  screen shown on the next launch.
- Sharing the built-in default calendar promotes the same visible calendar instead of
  leaving an empty personal calendar beside a separate shared copy.

## Core capabilities

- Review overdue tasks in one compact window, select only the items you want, and either
  bring them to today or mark them complete on their original dates.
- Keep recurring schedules, event records, and read-only calendars out of bulk overdue
  actions. Enter still cancels the window instead of triggering an accidental bulk action.

- Keep automatic planner and speaking-practice synchronization queued while invitation
  or shared-calendar polling is using the account connection.
- Upload pending edits before the next background poll. Normal editing after sign-in
  does not require pressing **Sync now** after every change.
- If Ubuntu contains work that has not reached Windows, update Ubuntu first without
  deleting `~/Documents/TAKT`, complete synchronization, and then synchronize Windows.

- Single-click a calendar cell to select its date, or double-click it to open the full
  schedule editor immediately. Right-click still opens the complete date action menu.
- Keep active Korean IME composition intact during background planner refreshes, including
  quick tasks, document titles, and document bodies. The final composing character is no
  longer cleared or lost.
- Choose start and end dates from a theme-aware range calendar and set a custom color
  for multi-day schedule bars.

- Open Existing calendar, Create calendar, Invite, or Inbox from one compact horizontal
  action row in My TAKT or the planner chain icon.
- Promote any existing local or cloud calendar to a shared calendar without creating a
  duplicate, keeping its schedules, repeats, documents, folders, and tags.
- Enter multiple TAKT account emails. Enter moves to the next address and invitations
  are sent only when the button is clicked.
- Keep typing while account synchronization runs in the background without losing focus.
- Open received invitations directly from the same chain-icon window.
- Import and export ICS files from one compact card.
- Review invitations from a compact mailbox and identify the inviter before deciding.
- Create, edit, complete, and delete shared schedules from the existing planner.
- Let owners manage invitations and members; members can safely leave a calendar.
- Start normally without an interactive keyring-creation prompt when no vault exists.
- Customize the outer background, timer, recorder, and planner cards independently,
  including separate opacity controls for all three work cards.
- TAKT 2.0.19 contains no payment flow or premium lock. Accounts created on or before
  February 28, 2027 remain free, including future updates. Accounts created from March 1,
  2027 are planned to require a KRW 2,900 paid entitlement. Payment method and detailed
  terms will be announced before the transition.

---

## 한국어 안내

집중 타이머, 일정과 문서 메모, 녹음 기반 말하기 연습을 한곳에서 사용하는
Ubuntu 데스크톱 앱입니다.

- [최신 Ubuntu 설치 파일 받기](https://github.com/TAKT-Flow/TAKT-FLOW/releases/latest)
- 지원 환경: Ubuntu 20.04 / 22.04 / 24.04 LTS, x86-64(amd64)

```bash
cd ~/Downloads
sudo apt install ./takt_2.0.19-1_amd64.deb
```

SHA-256:
`df7e590c3638b4bedb7b9c1aa821395636c8e70bed45b75ba65d6de6ab1448e3`

설치와 업데이트, 삭제 방법은 [설치 매뉴얼](설치-매뉴얼.md), 기능 사용법은
[사용 매뉴얼](사용-매뉴얼.md)을 확인하세요.

## 2.0.19 업데이트

- 캘린더 목록 우클릭에서 공유 사용자 목록을 열고 이름(메일)과 권한을 확인합니다.
  소유자와 공동 소유자만 각 사용자의 권한 콤보박스를 변경할 수 있습니다.
- 읽기·수정·관리자 권한으로 초대하고 소유권을 양도할 수 있습니다. 이전 소유자는
  모든 권한을 가진 공동 소유자로 남으며, 나가더라도 캘린더와 다른 구성원은 유지됩니다.
- 받은·보낸 초대 이력과 상태별 필터, 앱 내 확인·응답 시각을 초대함에서 봅니다.
  이메일 읽음 추적 기능은 아닙니다.
- 웹 일정 구독창과 일정·문서 요약창이 250% 등 작은 고배율 화면 안에서 스크롤되고
  닫기 버튼이 잘리거나 겹치지 않도록 수정했습니다.
- 2.0.18에서 준비한 달력·입력·반복 색상·동기화 개선도 포함합니다. 새 권한을 사용할
  협업 구성원은 모두 최신 버전으로 업데이트해 주세요.

- 긴 일정 요약 카드는 전체 글자가 보이도록 높이가 늘어납니다. 일정이 많으면 창은
  화면 안에서만 커지고 나머지는 내부 스크롤로 확인합니다.
- 캘린더 목록을 마우스 오른쪽 버튼으로 눌러 원하는 캘린더나 종합 캘린더를 다음
  실행에 먼저 열 메인 캘린더로 지정할 수 있습니다.
- 기본 캘린더 공유 시 빈 개인 캘린더와 별도 공유 복사본을 함께 만들지 않고 같은
  캘린더를 일정·반복·문서와 함께 공유 상태로 전환합니다.

## 주요 기능

- 지난 미완료 항목을 한 창에서 골라 오늘로 가져오거나, 원래 날짜를 유지한 채
  완료 처리할 수 있습니다.
- 반복 일정, 기록형 일정과 읽기 전용 캘린더는 일괄 정리에서 제외되며, Enter는
  실수로 대량 작업을 실행하지 않고 창을 취소합니다.

- 초대 또는 공유 캘린더 조회 중에도 일반 일정·메모·말하기 연습의 자동 동기화
  요청을 보관하고, 다음 백그라운드 조회보다 먼저 처리합니다.
- 로그인 후 일반적인 작성·수정에는 `지금 동기화`를 매번 누를 필요가 없습니다.
- Ubuntu 작업이 Windows에 나타나지 않았다면 `~/Documents/TAKT`를 삭제하지 말고
  Ubuntu부터 업데이트해 동기화를 완료한 뒤 Windows를 동기화하세요.

- 달력 셀은 한 번 클릭하면 날짜만 선택되고, 더블클릭하면 해당 날짜의 정식 일정
  추가 창이 바로 열립니다. 우클릭의 날짜 전체 메뉴는 그대로 유지됩니다.
- 백그라운드 플래너 갱신 중에도 빠른 할 일, 문서 제목과 본문에서 조합 중인 한글이
  초기화되지 않으며 마지막 글자도 사라지지 않습니다.
- 여러 날 일정의 날짜 선택 달력을 개선했고 일정 막대 색상을 직접 고를 수 있습니다.

- 내 정보 또는 달력의 사슬 아이콘에서 `기존 캘린더`, `캘린더 생성`, `초대하기`,
  `받은 초대`를 한 줄로 확인합니다.
- 로컬 또는 클라우드의 기존 캘린더를 중복 생성하지 않고 공유로 전환하며 일정, 반복,
  문서, 폴더와 태그를 그대로 유지합니다.
- 여러 이메일을 입력할 수 있습니다. Enter는 다음 입력칸으로 이동하고 실제 전송은
  `초대 보내기`를 클릭할 때만 진행됩니다.
- 계정 동기화가 백그라운드에서 실행되어도 이메일 입력 포커스를 유지합니다.
- 같은 사슬 아이콘 창에서 받은 초대함을 열고, ICS 가져오기·내보내기를 한곳에서 사용합니다.
- 간결한 편지 아이콘 초대함에서 발신자 정보를 확인한 뒤 수락하거나 거절합니다.
- 기존 플래너에서 공유 일정을 만들고 수정·완료·삭제할 수 있습니다.
- 소유자는 초대와 구성원을 관리하고, 구성원은 캘린더에서 안전하게 나갈 수 있습니다.
- 사용할 수 있는 키링이 없어도 생성 암호창을 띄우지 않고 정상 시작합니다.
- 외부 배경, 타이머, 녹음기, 달력·메모 카드를 따로 꾸미고 카드별 투명도를 조절합니다.
- 2.0.19에는 결제나 유료 기능 제한이 없습니다. 2027년 2월 28일까지 가입한 계정은
  이후 업데이트를 포함해 계속 무료입니다. 2027년 3월 1일 이후 신규 가입 계정은
  2,900원 유료 전환 예정이며, 결제 방식과 세부 기준은 전환 전에 별도 안내합니다.
