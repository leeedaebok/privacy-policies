# privacy-policies

앱별 개인정보처리방침을 GitHub Pages로 호스팅하는 저장소입니다.

**여기저기 흩어져 있던 방침을 이 저장소로 통일했습니다(2026-08-13).**
이전에는 앱마다 별도 GitHub Pages 저장소나 Google Docs를 쓰고 있어서, 어떤 앱의 방침이
어디에 있는지 추적이 안 되고 내용도 제각각이었습니다. 앞으로 새 앱을 추가할 때도 이 저장소만 씁니다.

| 앱 | 패키지명 | URL |
|---|---|---|
| 동네배움터 알리미 | com.bok.baeumteo | https://leeedaebok.github.io/privacy-policies/baeumteo/ |
| 밥픽 - 오늘 뭐 먹지? | com.bok.bobpick | https://leeedaebok.github.io/privacy-policies/bobpick/ |
| Bok 스토리지 매니저 | com.bok.storagemanager | https://leeedaebok.github.io/privacy-policies/bokstoragemanager/ |
| 매일 성경 통독 | com.bok.dailybible | https://leeedaebok.github.io/privacy-policies/dailybible/ |
| 똥피하기 | com.bok.ddongdodge | https://leeedaebok.github.io/privacy-policies/ddongdodge/ |
| EvidSnap | com.bok.evidsnap | https://leeedaebok.github.io/privacy-policies/evidsnap/ |
| Global Size Guide | com.bok.globalsizeguide | https://leeedaebok.github.io/privacy-policies/globalsizeguide/ |
| 사업공고 알리미 | com.bok.gonggoalimi | https://leeedaebok.github.io/privacy-policies/gonggoalimi/ |
| 하늘 - 어제 오늘 날씨 비교 | com.bok.haneul | https://leeedaebok.github.io/privacy-policies/haneul/ |
| 장날알리미 | com.bok.jangnalalimi | https://leeedaebok.github.io/privacy-policies/jangnalalimi/ |
| 칼로체크인 | com.bok.kalocheckin | https://leeedaebok.github.io/privacy-policies/kalocheckin/ |
| 산도장 - 봉우리 등산 도감 | com.bok.sandojang | https://leeedaebok.github.io/privacy-policies/sandojang/ |
| 사장님 세무캘린더 | com.bok.semucal | https://leeedaebok.github.io/privacy-policies/semucalendar/ |
| 한영심플성경 | com.bok.simplebible | https://leeedaebok.github.io/privacy-policies/simplebible/ |

## 대체된 이전 방침

아래 주소들은 이 저장소의 문서로 대체됐습니다. **Play Console의 개인정보처리방침 URL을 위 표의 주소로 바꿔야 합니다.**

| 앱 | 이전 위치 |
|---|---|
| 사업공고 알리미 | https://leeedaebok.github.io/gonggo-alimi-privacy/ |
| 동네배움터 알리미 | https://leeedaebok.github.io/baeumteo-privacy/ |
| EvidSnap | Google Docs (2026-05-14) |
| 장날알리미 | Google Docs (2026-04-26) |
| 한영심플성경 | Google Docs (2026-05-08) |
| Global Size Guide | Google Docs (2026-05-06) — 옮기면서 **Google Analytics for Firebase 항목을 새로 채웠습니다.** 원문에는 AdMob만 적혀 있었는데 앱은 실제로 Analytics를 쓰고 있었습니다 |

## 새 앱 추가 방법

1. `<앱이름>/index.html` 폴더와 파일을 만듭니다. `dailybible/index.html`을 복사해 쓰면 형식이 통일됩니다.
2. 루트 `index.html` 목록과 위 표에 링크를 추가합니다.
3. Play Console → 앱 콘텐츠 → 개인정보처리방침에 URL을 등록합니다.

## 작성 시 지켜야 할 것

- **Google Analytics for Firebase를 쓰는 앱은 반드시 명시합니다.** 광고(AdMob)만 적어두면 실제 수집과 어긋납니다.
- 앱이 실제로 선언한 권한만 적습니다(`AndroidManifest.xml` 확인).
- 분석 이벤트에 **무엇을 담지 않는지**도 적습니다. 좌표·주소·검색어·공고 제목 등은 수집하지 않으며, 이 점이 사용자에게 중요한 정보입니다.
- 국외 이전(Google LLC, 미국) 문구를 포함합니다.
