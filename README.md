# MyProject apps

광고 없이 쓰려고 만든 개인용 Windows 프로그램들의 실행 파일입니다. 소스는 비공개입니다.

| 프로그램 | 설명 |
|---|---|
| MyMemo | 바탕화면 메모 (음력·히브리력 달력) |
| MyZip | 압축 프로그램 (탐색기 메뉴 지원) |
| MyPlayer | 동영상 플레이어 (libmpv) |
| MyBrowser | 동영상 보기용 브라우저 (탭, 반화면 전체화면) |
| MyView | 이미지 뷰어 |
| MyCapture | 화면 캡처와 편집 (PrtSc) |
| MyBible | 성경 읽기 (Bethlehem 성경 데이터 필요) |

## 받기

[Releases](https://github.com/kozyi/MyProject-apps-releases/releases)에서 프로그램 이름으로 된 태그(예: `MyCapture-v1.0.2`)의 exe를 받으세요.

- [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0)이 필요합니다.
- 브라우저로 처음 받은 exe는 SmartScreen 경고가 뜰 수 있습니다. 파일 속성에서 "차단 해제"를 체크하거나 "추가 정보 → 실행"을 누르세요.

## 자동 업데이트

각 프로그램은 실행할 때(최대 하루 한 번) 이 저장소에서 새 버전을 확인하고, 있으면 업데이트할지 묻습니다.
받은 파일은 GitHub에 기록된 SHA-256으로 확인한 뒤 교체하고 다시 시작합니다.
`MYAPPS_NO_UPDATE` 환경 변수를 설정하면 확인하지 않습니다.

## 릴리스 규칙

- 태그: `<프로그램>-v<버전>` (버전은 프로젝트 파일의 `<Version>`과 같게)
- 첨부 파일: `<프로그램>.exe` 하나
