# 🧑‍💻 생성형 AI 기반 퀴즈 생성 사이트 개발 프로젝트

## 📌 프로젝트 소개  
코딩 테스트 외에 **체계적인 CS 학습**을 지원하는 플랫폼의 필요성을 느껴,  
주변 지인들과 함께 사용할 만한 **생성형 AI 기반의 퀴즈 생성 서비스**를 개발하였습니다.  
이 서비스는 **객관식, 참/거짓, 빈칸 채우기** 등의 퀴즈를 생성하고, 해설과 피드백을 제공합니다.  
또한, 퀴즈 기록 관리, 오답 노트, PDF 내보내기 기능도 제공합니다.

---

## 🚀 배포 및 리소스  
- **배포 링크**: [CS Hub](https://cs-hub-murex.vercel.app/)  

---

## 🛠 기술 스택  
| 분류        | 기술  |
|------------|--------------------------|
| **개발 언어**  | TypeScript |
| **프레임워크** | React |
| **스타일링** | styled-components |
| **상태관리** | Zustand |
| **배포 및 인프라** | Vercel |
| **버전 관리** | Git |

---

## ✨ 주요 기능  
- 🔄 **퀴즈 생성**: 객관식, 참/거짓, 빈칸 채우기 등 다양한 형태의 퀴즈 생성  
- 📊 **해설 및 피드백 제공**: 각 퀴즈에 대한 해설과 피드백 제공  
- 📂 **기록 관리**: 퀴즈 결과 기록 및 오답 노트 관리  
- 📝 **PDF 내보내기**: 퀴즈 결과를 PDF로 내보낼 수 있는 기능

---

## 🛠 문제 해결 경험  
### ✅ 레이아웃 시프트 문제 해결  
- 초기 로딩 시 발생한 **레이아웃 시프트(layout shift)** 문제를 해결하기 위해  
  이미지 요소에 **크기 명시**, 폰트에 **display: swap** 옵션을 추가했습니다.

### ✅ 성능 최적화  
- 렌더링 차단 리소스를 줄이기 위해 **FontAwesome** 라이브러리를 **preload**로 설정하여  
  브라우저가 우선적으로 다운로드하도록 했습니다.  
- 특정 페이지에서만 사용되는 패키지에 **lazy loading**을 도입하여 번들 사이즈를 줄였습니다.

- **결과**: Lighthouse 성능 점수를 **67점 → 87점**으로 개선할 수 있었습니다.

### ✅ 새로운 기술 도입  
- **Styled Components**와 **Framer-motion**의 조합을 통해 UI와 애니메이션을 적용하여  
  새로운 기술에 대한 저항을 줄이고 익숙해지는 데 도움을 받았습니다.

---

## 👨‍💻 팀 구성 및 역할  
| 역할 | 인원 | 담당 업무 |
|------|------|-------------------------|
| **개발자** | 1명 | 퀴즈 생성 서비스 개발, UI 구현 |

---

## 🔍 회고  
### 🌟 좋았던 점  
- 오랜만에 **혼자서 원하던 기능 구현에 집중**하며 부담 없이 개발을 진행할 수 있었던 점은 만족스러웠습니다.

### 😢 아쉬웠던 점  
- 생각보다 **기획안과 같은 문서 작성**에 많은 시간이 할애되면서,  
  초반에 **최적화에 충분히 집중하지 못한 점**이 아쉬웠습니다.

---

## 퀴즈 주제 정하기
<div style="display: flex; justify-content: space-between; align-items: flex-start;">
   <img width="65%" alt="스크린샷 2024-10-04 오후 12 57 04" src="https://github.com/user-attachments/assets/b6cc028c-86fa-4497-981b-694b2fd3524c">
   <img width="25%" alt="스크린샷 2024-10-04 오후 12 29 29" src="https://github.com/user-attachments/assets/1e3b7928-bde8-4104-903f-7137a8ab1bad">
</div>

## 퀴즈 풀이 화면 
<div style="display: flex; justify-content: space-between; align-items: flex-start;">
   <img width="65%" alt="스크린샷 2024-09-30 오전 10 06 27" src="https://github.com/user-attachments/assets/8582fa14-251f-4b45-9b5a-17619f7eb76a">
   <img width="25%" alt="스크린샷 2024-10-04 오후 12 52 28" src="https://github.com/user-attachments/assets/67cf4a90-429c-4d31-b601-e29ea515d8c3">
</div>

## 퀴즈 결과 확인 
<div style="display: flex; justify-content: space-between; align-items: flex-start;">
   <img width="65%" alt="스크린샷 2024-09-30 오후 4 50 04" src="https://github.com/user-attachments/assets/87cfa867-cb14-41a2-99d6-f2a4744b1adb">
   <img width="25%" alt="스크린샷 2024-10-04 오후 12 29 29" src="https://github.com/user-attachments/assets/1e3b7928-bde8-4104-903f-7137a8ab1bad">
</div>

## 오답노트
<div style="display: flex; justify-content: space-between;">
   <img width="65%" alt="스크린샷 2024-10-04 오후 12 55 48" src="https://github.com/user-attachments/assets/9b07162e-b505-4385-b2c3-16672d24e00c">
   <img width="25%" alt="스크린샷 2024-10-04 오후 12 25 16" src="https://github.com/user-attachments/assets/0d570653-6766-4cf8-8807-c7a21c5c385b">
</div>
