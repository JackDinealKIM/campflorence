# 가평 플로렌스 글램핑 웹사이트

가평 플로렌스 글램핑의 공식 웹사이트입니다. 경기도 가평에 위치한 프리미엄 글램핑 캠핑장의 시설 소개, 객실 안내, 예약 시스템을 제공합니다.

## 🏕️ 프로젝트 개요

**웹사이트**: [www.campflorence.com](https://www.campflorence.com)

가평 플로렌스 글램핑은 4천평 규모의 넓은 부지에 천연 지하수 수영장과 프라이빗 불멍존을 갖춘 프리미엄 글램핑 캠핑장입니다. 서울에서 1시간 거리의 청정 자연 속에서 특별한 캠핑 경험을 제공합니다.

## 🛠️ 기술 스택

- **프론트엔드**: HTML5, CSS3, JavaScript (ES6+)
- **빌드 도구**: Vite 6.0.5
- **의존성 관리**: npm
- **배포**: GitHub Pages (CNAME 설정)
- **애널리틱스**: Google Analytics 4
- **SEO**: 구조화된 데이터, Open Graph, Twitter Cards

## 📁 프로젝트 구조

```
campflorence/
├── index.html                    # 메인 페이지
├── room.html                     # 객실 안내
├── activity.html                 # 액티비티 소개
├── faq.html                      # 자주 묻는 질문
├── room-details-family.html      # 가족 글램핑 상세
├── room-details-couple.html      # 커플 글램핑 상세
├── gallery-*.html                # 각종 갤러리 페이지들
├── css/
│   ├── style.css                 # 메인 스타일시트
│   ├── common.css                # 공통 스타일
│   ├── plugins.css               # 플러그인 스타일
│   └── plugins/                  # 플러그인 CSS 파일들
├── js/
│   ├── custom.js                 # 커스텀 JavaScript
│   ├── jquery-3.7.1.min.js      # jQuery 라이브러리
│   ├── bootstrap.min.js          # Bootstrap 프레임워크
│   ├── owl.carousel.min.js       # 캐러셀 슬라이더
│   └── ...                       # 기타 플러그인들
├── image/                        # 이미지 리소스
├── video/                        # 비디오 리소스
├── fonts/                        # 웹폰트 파일들
├── dist/                         # 빌드 결과물
├── package.json                  # 프로젝트 설정
├── vite.config.js                # Vite 설정
├── CNAME                         # GitHub Pages 도메인 설정
└── sitemap.xml                   # 검색엔진 최적화
```

## 🚀 개발 환경 설정

### 필수 조건
- Node.js (권장: v16 이상)
- npm

### 설치 및 실행

```bash
# 의존성 설치
npm install

# 개발 서버 실행 (로컬 개발용)
npm run dev

# 프로덕션 빌드
npm run build

# 빌드 결과 미리보기
npm run preview

# 파일 복사 (배포용)
npm run copy
```

## 🎯 주요 기능

### 웹사이트 기능
- **반응형 디자인**: 모바일, 태블릿, 데스크톱 최적화
- **이미지 갤러리**: 캠핑장 시설별 사진 갤러리
- **객실 상세 정보**: 가족형/커플형 글램핑 텐트 소개
- **액티비티 안내**: 수영장, 바베큐, 캠프파이어 등
- **실시간 예약 연동**: 외부 예약 시스템 연동
- **카카오톡 문의**: 실시간 고객 상담

### SEO 최적화
- 구조화된 데이터 (JSON-LD)
- Open Graph 메타태그
- Twitter Cards
- 사이트맵 생성
- 검색엔진 친화적 URL 구조

## 📱 지원 페이지

| 페이지 | 파일명 | 설명 |
|--------|--------|------|
| 메인 | `index.html` | 캠핑장 소개 및 메인 정보 |
| 객실 안내 | `room.html` | 글램핑 텐트 타입 소개 |
| 가족 글램핑 | `room-details-family.html` | 4인용 럭셔리 텐트 상세 |
| 커플 글램핑 | `room-details-couple.html` | 2-3인용 스탠다드 텐트 상세 |
| 액티비티 | `activity.html` | 캠핑장 내 즐길거리 소개 |
| FAQ | `faq.html` | 자주 묻는 질문 |
| 갤러리 | `gallery-*.html` | 시설별 사진 갤러리 |

## 🔧 주요 라이브러리

- **jQuery 3.7.1**: DOM 조작 및 이벤트 처리
- **Bootstrap**: 반응형 레이아웃 프레임워크
- **Owl Carousel**: 이미지 슬라이더
- **Magnific Popup**: 이미지 팝업
- **Select2**: 드롭다운 개선
- **Waypoints**: 스크롤 애니메이션
- **Vegas Slider**: 배경 슬라이더

## 🌐 배포

이 프로젝트는 GitHub Pages를 통해 자동 배포됩니다.

- **도메인**: www.campflorence.com
- **배포 방식**: GitHub Pages + 커스텀 도메인
- **빌드**: Vite를 통한 정적 사이트 생성

## 📞 연락처 및 예약

- **전화**: 010-2925-1020
- **이메일**: didajfn@nate.com
- **카카오톡 문의**: [오픈채팅방](https://open.kakao.com/o/s94EJgch)
- **실시간 예약**: [예약 시스템](https://booking.ddnayo.com/booking-calendar-status?accommodationId=104535)

## 📍 위치 정보

- **주소**: 경기도 가평군 북면 목동리 1077-2
- **접근성**: 
  - 설악 IC에서 49분
  - 화도 IC에서 54분
- **좌표**: 37.8929165, 127.5504989

## 🎪 캠핑장 특징

- **규모**: 약 4천평 부지
- **객실**: 가족형(4인) / 커플형(2-3인) 글램핑 텐트
- **시설**: 천연 지하수 수영장, 프라이빗 불멍존, 바베큐존
- **편의시설**: 깨끗한 화장실/샤워실, 무료 Wi-Fi, 전기시설
- **액티비티**: 수영, 바베큐, 캠프파이어, 계곡 물놀이

## 📈 SEO 및 마케팅

- Google Analytics 4 연동
- 네이버 사이트 인증
- 구조화된 데이터로 검색 최적화
- 소셜 미디어 메타태그 설정
- 사이트맵 및 robots.txt 관리

---

**Copyright © 2024 가평 플로렌스 글램핑. All rights reserved.**
