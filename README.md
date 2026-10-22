# 하루결 — 날씨와 계산기가 있는 생산성 앱

오늘의 날씨를 확인하고, 할 일을 정리하고, 집중 시간을 관리할 수 있는 **한 페이지 대시보드**입니다. 별도의 회원가입 없이 브라우저에서 바로 사용할 수 있습니다.

👉 **[앱 바로 열기](https://wjij08koreakr-hue.github.io/harugyeol-productivity-app/)**

## 무엇을 할 수 있나요?

| 기능 | 사용 방법 |
| --- | --- |
| ☀️ 오늘의 날씨 | 기본으로 서울 날씨가 표시됩니다. 검색창에 도시 이름을 입력하면 다른 지역의 기온·습도·풍속·체감온도를 볼 수 있습니다. |
| 🧮 계산기 | 사칙연산, 소수점, 백분율, 부호 변경을 지원합니다. 키보드의 숫자와 연산 기호, `Enter`(계산), `Backspace`(지우기), `Escape`(초기화)도 사용할 수 있습니다. |
| ✅ 할 일 목록 | 할 일을 추가하고 체크해 완료할 수 있습니다. 진행률이 자동으로 표시됩니다. |
| ⏱️ 집중 타이머 | 집중 25분, 짧은 휴식 5분, 긴 휴식 15분 중 선택해 시작·일시정지·초기화할 수 있습니다. |
| 📝 빠른 메모 | 생각을 적으면 자동으로 저장됩니다. |

할 일, 메모, 마지막으로 검색한 도시는 **사용 중인 브라우저의 로컬 저장소**에 보관됩니다. 같은 브라우저에서 다시 열면 남아 있지만, 다른 기기나 브라우저로 자동 동기화되지는 않습니다. 브라우저 데이터를 삭제하면 함께 지워질 수 있습니다.

## 사용하기

### 가장 쉬운 방법

위의 **[앱 바로 열기](https://wjij08koreakr-hue.github.io/harugyeol-productivity-app/)** 링크를 누르세요. 휴대폰과 PC에서 모두 사용할 수 있습니다.

### 내 컴퓨터에서 열기

1. 이 저장소에서 `index.html`을 내려받습니다.
2. 파일을 더블클릭해 브라우저에서 엽니다.

설치하거나 서버를 실행할 필요는 없습니다. 다만 **실시간 날씨와 웹 글꼴을 불러오려면 인터넷 연결이 필요**합니다. 날씨 정보는 계정이나 API 키가 필요 없는 [Open-Meteo](https://open-meteo.com/)를 사용합니다.

## 코드를 수정하고 다시 배포하기

화면 디자인과 기능은 모두 [`index.html`](index.html)에 들어 있습니다. 파일을 수정한 뒤 저장소 폴더에서 다음 명령을 실행하면 GitHub Pages가 변경 내용을 자동으로 반영합니다.

```bash
git add index.html
git commit -m "화면 또는 기능 수정"
git push
```

처음 다른 컴퓨터에서 작업한다면 [Git](https://git-scm.com/)을 설치한 후 저장소를 복제하세요.

```bash
git clone https://github.com/wjij08koreakr-hue/harugyeol-productivity-app.git
cd harugyeol-productivity-app
```

배포 주소는 **https://wjij08koreakr-hue.github.io/harugyeol-productivity-app/** 입니다. 푸시 직후에는 반영까지 잠시 걸릴 수 있습니다.

## 프로젝트 구성

```text
harugyeol-productivity-app/
├── index.html   # 화면, 스타일, 기능을 담은 단일 파일
└── README.md    # 지금 보고 있는 안내 문서
```

HTML, CSS, JavaScript만 사용했으며 별도의 빌드 과정이나 패키지 설치가 필요하지 않습니다. GitHub Pages로 호스팅합니다.
