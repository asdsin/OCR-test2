# OCR-test2 Mobile Test Guide

## 1) GitHub Pages 켜기 (한 번만)

1. 저장소 `Settings` 로 이동
2. `Pages` 메뉴 선택
3. `Build and deployment` 에서
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. `Save`

배포가 끝나면 아래 주소로 모바일 접속:

- `https://asdsin.github.io/OCR-test2/`

## 2) 모바일 테스트 순서

1. 주소 접속 후 `판정 화면 열기`
2. 로그인
   - `admin / 1234`
   - `worker1 / 0000`
3. 카메라 권한 허용
4. `🧪 데모` 버튼으로 기본 동작 확인
5. 실제 QR 또는 수동 입력으로 설비 식별 후 촬영 테스트

## 3) 체크포인트

- QR 인식 후 설비 식별이 정상 동작하는지
- 촬영 + OCR 결과 카드가 생성되는지
- 학습 보정 등록 후 재촬영 시 보정이 반영되는지
- 판정 이력 저장/조회가 되는지

## 4) 참고

- 현재 버전은 PWA 등록 코드를 제거한 일반 웹 배포본입니다.
