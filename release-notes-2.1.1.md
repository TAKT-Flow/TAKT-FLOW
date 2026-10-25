# TAKT FLOW 2.1.1

## Public Holidays And Calendar Cleanup

- Korean national holidays are displayed offline by default. Search 250
  countries/territories, or turn display off, from Settings > Public holidays
  directly below Language. This computer remembers the choice.
- Holiday dates and their fixed first content row are red. Holiday rows are
  display-only, not user events or document notes. Newly declared holidays need
  an app/data update; regional/state holidays can differ.
- Calendar cells no longer reserve unused top space. User rows keep their input
  order, including completed tasks; multi-day bars remain connected.
- Late row measurements keep the bottom input visible in crowded days, while
  respecting an intentional scroll to earlier items.
- Personal-calendar removal offers a destination selector with Default
  preselected and separate Move / Delete actions. Move preserves contents;
  Delete removes the selected calendar and its contents. File failures keep
  the calendar, events and documents and explain any partially deleted files.
- Existing accounts, other calendars, files, backgrounds and permissions remain
  in place. No server migration or new payment flow is required.

Ubuntu: `takt_2.1.1-1_amd64.deb`, x86-64, Ubuntu 22.04+ / Python 3.10+.
Ubuntu 20.04 users can retain the archived 2.0.26 release.
Windows updates are distributed separately through Microsoft Store and become
available after Microsoft's certification and publishing steps.

## 한국어 안내

- 한국 공휴일을 기본 표시합니다. 설정 > 언어 아래의 공휴일에서 국가를
  검색하거나 표시를 끄며, 인터넷·로그인·추가 비용 없이 작동합니다.
- 공휴일은 날짜와 셀 첫 줄의 빨간 막대로 표시합니다. 일정·메모에는
  추가하지 않으며 새로 지정된 임시공휴일은 앱 업데이트가 필요합니다.
- 셀의 불필요한 위쪽 여백을 줄이고 일정은 입력 순서대로 표시합니다.
- 개인 캘린더 삭제 창에서 기본 대상을 선택한 뒤 옮기기 또는 삭제를
  고릅니다. 옮기기는 내용을 보관하며 삭제는 내용까지 지웁니다.
- 기존 계정과 다른 캘린더 자료는 유지합니다. Ubuntu 22.04 이상을 지원하며
  20.04는 기존 2.0.26을 계속 사용할 수 있습니다.

The release includes a reviewed 36-page PDF and self-contained offline HTML
manual, with Korean instructions, an English quick guide and 12 example-data
application screenshots. Checksums are listed in `SHA256SUMS.txt`.
