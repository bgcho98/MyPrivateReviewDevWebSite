# My Private Review - 개발 문서

## 프로젝트 개요
- **앱 이름**: My Private Review
- **플랫폼**: Flutter (Android/iOS)
- **목적**: 개인 리뷰 관리 앱

## 기술 스택
- **프레임워크**: Flutter
- **데이터베이스**: Hive (로컬 저장)
- **상태 관리**: StatefulWidget
- **광고**: Google AdMob
- **지도**: Google Maps

## 주요 기능
1. **리뷰 추가**: 상점, 제품, 리뷰 내용, 평점 저장
2. **리뷰 검색**: 저장된 리뷰 검색 기능
3. **자동 완성**: 이전 입력 기반 자동 완성
4. **로컬 저장**: 모든 데이터 기기 내 저장

## 아키텍처
```
lib/
├── main.dart              # 앱 진입점
├── home_screen.dart       # 홈 화면
├── add_review_screen.dart # 리뷰 추가 화면
└── search_screen.dart     # 검색 화면
```

## 개발 진행 상황
- [x] 기본 UI 구현
- [x] 리뷰 추가 기능
- [x] 리뷰 검색 기능
- [x] 릴리즈 빌드 설정
- [x] Play Console 업로드 준비

## 이슈 및 해결 사항
### 2024-01-01: 릴리즈 모드 Save 버튼 오류
- **문제**: 릴리즈 모드에서 Save 버튼 작동 안 함
- **원인**: R8 최적화로 인한 클래스 제거
- **해결**: ProGuard 규칙 추가

### 2024-01-01: Play Console 업로드 오류
- **문제**: 동일 버전 충돌
- **해결**: 버전 코드 증가 (1.0.0+1 → 1.0.1+2)

## 다음 단계
1. 개인정보처리방침 호스팅
2. Play Console 앱 설명 작성
3. 스크린샷 준비
4. 베타 테스트 진행

## 참고 링크
- [Flutter 공식 문서](https://flutter.dev/docs)
- [Hive 문서](https://docs.hivedb.dev/)
- [Play Console 가이드](https://developer.android.com/distribute/console) 