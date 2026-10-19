# TAKT FLOW for Ubuntu

TAKT FLOW combines focus timers, planning, document notes, recording, speaking
practice, and desktop widgets in one English/Korean Ubuntu workspace.

## Download and install

- [Download the latest Ubuntu release](https://github.com/TAKT-Flow/TAKT-FLOW/releases/latest)
- Supported: Ubuntu 20.04 / 22.04 / 24.04 LTS, x86-64 (amd64)

```bash
cd ~/Downloads
sudo apt install ./takt_2.0.24-1_amd64.deb
```

SHA-256:
`9a39aab9597d71efb50bd7ce9beec60edd4a7e06a251912c394c1709d3387b1f`

See the [installation guide](설치-매뉴얼.md) and [2.0.24 user manual](사용-매뉴얼.md)
([English quick guide](사용-매뉴얼.md#english)). The manual covers first launch, startup
settings, all five views, widgets, shared access and detailed input with 12 actual
application screenshots using example data.

**Manual formats (2.0.24):** [Read online](https://takt-download.rldndprogram.chatgpt.site/manual.html) · [Download PDF](https://github.com/TAKT-Flow/TAKT-FLOW/releases/download/v2.0.24/TAKT-FLOW-User-Manual-2.0.24.pdf) · [Download offline HTML](https://github.com/TAKT-Flow/TAKT-FLOW/releases/download/v2.0.24/TAKT-FLOW-User-Manual-2.0.24.html)

The reviewed PDF has 33 searchable pages and chapter bookmarks. The standalone
HTML includes all screenshots for offline use. The full guide is Korean with an
English quick guide; no separate app or installation is needed to read it.

**매뉴얼 보기·저장:** [웹에서 읽기](https://takt-download.rldndprogram.chatgpt.site/manual.html) · [PDF 다운로드](https://github.com/TAKT-Flow/TAKT-FLOW/releases/download/v2.0.24/TAKT-FLOW-User-Manual-2.0.24.pdf) · [HTML 다운로드](https://github.com/TAKT-Flow/TAKT-FLOW/releases/download/v2.0.24/TAKT-FLOW-User-Manual-2.0.24.html)

PDF는 33쪽으로 목차·책갈피·한글 검색을 지원합니다. HTML은 화면 이미지가
포함된 단일 파일이므로 내려받은 뒤 인터넷 없이 브라우저에서 열 수 있습니다.
This repository contains only the Ubuntu package and user documentation; app source
and Windows installers are maintained separately.

## 2.0.24 highlights

- Choose branded Kakao, Google or email entry buttons. Use sign-in help and a
  verified-email password reset without changing account identity or calendar data.
- Use accessible palette/monitor icons in the calendar widget and simple,
  background-free controls in the mini timer and main widget toolbar.
- Replace the permanent recording/sound footer with transient overlays. Keep
  persistent save-failure guidance and Retry, with balanced outer spacing.
- Reduce repeated photo resampling and calendar font calculations during live
  edge resizing; retain live text/layout and rebuild the photo at release.
- Include a refreshed 33-page PDF and self-contained HTML guide with current
  screenshots. Accounts, calendars, permissions and login methods stay unchanged.

## Included from 2.0.23

- Treat the default calendar on your own devices as one personal calendar,
  distinct from sharing with other people. Preserve existing IDs and content.
- Reconcile safe account changes automatically and ask only for genuine conflicts.
- Identify the startup calendar with bold text, separate from the current-view check.
- Keep combo lists and management menus stable during background polling, while
  retaining permission, account and in-flight-operation safety checks.
- Use calendar-add, members, refresh and gear icons in that order. Recover space
  from the smaller toolbar for the calendar; use a roomier weekday row that also
  shrinks with the date rows in compact windows.
- Remove transient small controls during detailed editing and the thick selected
  schedule outline. Includes the updated 32-page PDF and offline HTML manual.
- Use responsive, branded Korean/English browser guidance for Google/Kakao
  authentication, with distinct cancellation/error states and final results in TAKT.
- Keep selection-only saves responsive while preserving ordered atomic writes.
  Content saves, backups and normal exit wait for durable completion. Protect
  unsaved edits and interrupted account switches from incorrect sync uploads.

## Included from 2.0.22

- Sign up with Google or Kakao, or link them from an existing TAKT account.
  Email sign-in and existing calendars remain available. Use the account email
  displayed in My account when sending calendar invitations.
- Invite through a compact calendar selector; create a calendar from its last row.
  Add or remove eligible members from the shared-user list with confirmation.
- Keep a confirmed calendar creation request when background synchronization
  starts during its naming dialog; process it after the background task finishes.
- Keep open selectors stable during background refreshes and use consistent,
  rounded menu styling for shared roles and all authored combo lists.
- Improved theme/DPI tooltips and member/refresh icons.
- Preserve new practice records during background uploads and avoid redundant
  local writes that could stall the interface on slower storage.
- Open the version-matched GitHub manual or download PDF from the welcome screen
  or Settings > User manual. Offline HTML is also included in the release.

## Included from 2.0.21

- Choose Focus timer, Speaking practice, Work flow, Calendar or All features
  from the first-launch screen. Calendar opens the existing Plan today view.
- Switch the welcome screen with the upper-right English / 한국어 button.
  Choosing a workspace on first launch applies the selected application language
  immediately. Changing it from Help takes effect on the next launch.
- All choices remain reachable on small screens and at 250% scaling through
  internal scrolling and keyboard navigation.
- The illustrated manual covers startup settings, all five views, widgets,
  Shift+Enter, sharing, synchronization and backup in 14 sections and 12 screenshots.

## Included from 2.0.20

- Appearance card gaps, rounded corners and scrollbars follow the selected app
  theme even when the operating system uses the opposite theme.
- The appearance dialog keeps Apply and Cancel reachable on constrained screens,
  including at 250% scaling, by scrolling its content instead of clipping controls.
- Header menu arrows align to the physical pixel grid at fractional scaling,
  preserving their native outline across odd/even button sizes and positions.
- Existing accounts, saved sessions, calendars and notes are preserved. No server
  SQL changes or additional sign-in steps are required.

## Included from 2.0.19

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
- TAKT 2.0.23 contains no payment flow or premium lock. Accounts created on or before
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
sudo apt install ./takt_2.0.23-1_amd64.deb
```

SHA-256:
`c6eb3405a5323be1c87edb1a20652a36eb1aee465deb8b3f1f35e5b3a8cda7ad`

설치와 업데이트, 삭제 방법은 [설치 매뉴얼](설치-매뉴얼.md), 기능 사용법은
[2.0.23 사용 매뉴얼](사용-매뉴얼.md)을 확인하세요. 초기 화면·자동 실행·모드별 사용법·
위젯·Shift+Enter·공유 권한·백업을 14개 절과 실제 예시 화면 12장으로 안내합니다.

## 2.0.23 업데이트

- 기본 캘린더의 기기 동기화와 다른 사람과의 공유를 구분하고 기존 자료를 유지합니다.
- 안전한 변경은 자동 동기화하며 실제 충돌이 있을 때만 선택을 요청합니다.
- 시작 캘린더는 굵게 표시하고 메뉴·선택 목록의 갱신 중 깜빡임을 개선했습니다.
- 달력 추가·공유·새로고침·관리 순서로 아이콘을 정리하고 툴바 공간을 줄였습니다.
  일~토 요일 행은 넉넉하게 하되 작은 창에서는 날짜 행과 함께 줄어듭니다.
- 상세 수정 시 작은 창이 잠깐 나타나는 현상과 일정 선택의 굵은 테두리를 제거했습니다.
- Google·카카오 브라우저 인증 안내를 한영·밝은/어두운 화면에 맞게 정리했습니다.
- 실제 예시 화면을 갱신한 32쪽 PDF와 오프라인 HTML 매뉴얼을 제공합니다.
- 화면 선택 저장의 지연을 줄이고 내용 저장·백업·종료 시 저장 완료를 확인합니다.
  저장 실패와 계정 전환 중 중단 상황에서도 잘못된 동기화 업로드를 방지합니다.

## 2.0.22 포함 기능

- Google·카카오로 가입/로그인하거나 기존 TAKT 계정에서 연결할 수 있습니다.
  기존 이메일 로그인과 자료를 유지하며 초대에는 내 정보에 표시된 메일을 사용합니다.
- 공유 사용자 목록에서 사용자 추가·권한 변경·내보내기를 처리하고,
  캘린더 선택 목록의 마지막 항목에서 새 캘린더를 만들 수 있습니다.
- 선택 목록이 배경 갱신 중 닫히지 않게 하고, 메뉴 스타일과 툴팁·아이콘을 다듬었습니다.
- 설정과 첫 시작 화면에서 버전에 맞는 GitHub 매뉴얼과 PDF를 열 수 있습니다.
- 캘린더 전환 시 조회를 재사용하고 업로드 완료 시 중복 저장을 줄였습니다.
  업로드 중 새로 작성한 말하기 기록도 그대로 보존합니다.

## 2.0.21 포함 기능

- 첫 시작 화면에서 집중 타이머, 실전 말하기 연습, 업무 흐름, 캘린더, 모든 기능
  보기 중 선택합니다. 캘린더는 기존 오늘 일정 정리 모드를 엽니다.
- 오른쪽 위 English / 한국어 버튼으로 시작 화면을 바로 전환합니다. 첫 실행에서
  모드를 선택하면 앱 언어도 즉시 적용되며, 도움말에서 바꾸면 다음 실행에 적용됩니다.
- 작은 화면과 250% 배율에서도 내부 스크롤과 키보드로 모든 항목을 선택할 수 있습니다.
- 사용자 매뉴얼을 초기 화면, 자동시작, 각 모드, 위젯, Shift+Enter, 공유·동기화·백업의
  14개 절과 실제 예시 화면 12장으로 보강했습니다.

## 2.0.20 포함 기능

- 시스템 테마와 앱 테마가 달라도 창 꾸미기의 카드 사이 배경, 둥근 모서리와
  스크롤바가 선택한 앱 테마를 따릅니다.
- 250% 같은 고배율 화면에서 창 꾸미기 내용은 내부 스크롤되고 적용·취소 버튼은
  화면 안에 유지됩니다.
- 녹음·화면·설정·도움·더보기 화살표를 물리 픽셀 격자에 맞춰 그려 버튼의 홀짝
  크기와 위치 때문에 고배율에서 화살표 외곽이 달라지는 문제를 수정했습니다.
- 기존 계정, 저장된 로그인 상태, 일정과 메모는 유지됩니다. 서버 SQL이나 추가
  로그인 절차를 사용자가 실행할 필요가 없습니다.

## 2.0.19 포함 기능

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
  `초대함`을 한 줄로 확인합니다.
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
- 2.0.23에는 결제나 유료 기능 제한이 없습니다. 2027년 2월 28일까지 가입한 계정은
  이후 업데이트를 포함해 계속 무료입니다. 2027년 3월 1일 이후 신규 가입 계정은
  2,900원 유료 전환 예정이며, 결제 방식과 세부 기준은 전환 전에 별도 안내합니다.
