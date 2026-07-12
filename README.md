# 🔭 FITS 파일 뷰어

천문학 이미지(FITS 형식)를 업로드하고 시각화하며 분석하는 웹 애플리케이션입니다.

## 기능

✨ **FITS 파일 업로드**
- 드래그 앤 드롭으로 쉬운 업로드
- `.fits`, `.fit`, `.fts` 형식 지원

📊 **이미지 시각화**
- 이미지 렌더링
- 자동 명도 조정

📈 **데이터 분석**
- 픽셀 값 통계 (최소, 최대, 평균, 표준편차)
- 히스토그램 생성
- FITS 헤더 정보 표시

🔍 **메타데이터 추출**
- 이미지 크기
- 노출 시간
- 망원경 정보
- 필터 정보
- FITS 헤더 전체 정보

## 사용 방법

1. 웹사이트 열기: [GitHub Pages 링크]
2. FITS 파일 업로드 (드래그 드롭 또는 클릭)
3. 이미지 확인 및 정보 분석

## 기술 스택

- **HTML5** - 구조
- **CSS3** - 스타일링
- **JavaScript** - 기능 구현
- **Astropy FITS** - FITS 파일 파싱
- **Canvas API** - 이미지 렌더링

## 설치 및 실행

### 로컬에서 실행
```bash
# 저장소 클론
git clone https://github.com/YOUR_USERNAME/astro6.git
cd astro6

# 웹 서버 실행 (Python)
python -m http.server 8000

# 브라우저에서 열기
http://localhost:8000
