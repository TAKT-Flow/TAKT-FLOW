# TAKT FLOW for Ubuntu

TAKT FLOW combines focus timers, planning, document notes, recording, speaking
practice, and desktop widgets in one English/Korean Ubuntu workspace.

## Download and install

- [Download the latest Ubuntu release](https://github.com/TAKT-Flow/TAKT-FLOW/releases/latest)
- Supported: Ubuntu 20.04 / 22.04 / 24.04 LTS, x86-64 (amd64)

```bash
cd ~/Downloads
sudo apt install ./takt_2.0.13-1_amd64.deb
```

SHA-256:
`557e0b2dab7ef5d88dc671c501fba979a14eb80126d89f1894204be8e9f4d3e0`

See the [installation guide](설치-매뉴얼.md) and [user guide](사용-매뉴얼.md).
This repository contains only the Ubuntu package and user documentation; app source
and Windows installers are maintained separately.

## 2.0.13 highlights

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
- Account, invitation, and Windows/Ubuntu synchronization features remain free.

---

## 한국어 안내

집중 타이머, 일정과 문서 메모, 녹음 기반 말하기 연습을 한곳에서 사용하는
Ubuntu 데스크톱 앱입니다.

- [최신 Ubuntu 설치 파일 받기](https://github.com/TAKT-Flow/TAKT-FLOW/releases/latest)
- 지원 환경: Ubuntu 20.04 / 22.04 / 24.04 LTS, x86-64(amd64)

```bash
cd ~/Downloads
sudo apt install ./takt_2.0.13-1_amd64.deb
```

SHA-256:
`557e0b2dab7ef5d88dc671c501fba979a14eb80126d89f1894204be8e9f4d3e0`

설치와 업데이트, 삭제 방법은 [설치 매뉴얼](설치-매뉴얼.md), 기능 사용법은
[사용 매뉴얼](사용-매뉴얼.md)을 확인하세요.

## 2.0.13 업데이트

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
- 계정·초대·Windows/Ubuntu 동기화 기능은 계속 무료입니다.
