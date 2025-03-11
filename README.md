# MapB
kakao map api에 대한 테스트 작성입니다.

25.03.11.
테스트 주소 : https://huiib.kr/p1/
feat: 쿠키 기반 경로 저장/불러오기 및 지도 하단 거리·시간 표시 기능 추가

- (EgID E100) saveRoute(): 경로를 쿠키에 저장하는 함수
- (EgID E101) loadRoute(): 쿠키에서 경로를 불러와 지도에 표시하고, 클릭 이벤트를 비활성화
- (EgID E102) mapClickHandler(): 지도 클릭 이벤트를 통해 폴리라인 생성/추가
- (EgID E103, E104, E106~E108) 커스텀오버레이 생성/삭제 및 기존 경로 초기화 로직
- (EgID E105) updateRouteInfo(): 지도 하단에 총거리/도보/자전거/바이크 시간 표시
- (EgID E109, E110) 분(minutes) 포맷팅과 예상 시간 커스텀오버레이 HTML 생성

* 추후 쿠키 데이터를 벡엔드에서 데이터베이스로 처리할 것.
