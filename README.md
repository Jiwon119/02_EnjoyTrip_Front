# 02_EnjoyTrip_Front

## 요구사항
- 지역별 관광지 정보 수집 - 한국관광공사 : 지역별 관광지 정보를 얻어와 화면에 표시
- 관광지, 숙박, 음식점 조회 - 관광지 정보를 지역별 원하는 컨텐츠 별 조회.
- 문화시설, 공연, 여행코스, 쇼핑 조회 - 관광지 정보를 지역별 원하는 컨텐츠 별 조회.
- 회원 관리 - 회원가입, 수정, 조회, 탈퇴
- 로그인 관리 - 로그인 / 로그아웃 / 비밀번호 찾기

## 1. 메인 화면 - 여행지 선택 기능
메인 화면에는 웹 페이지의 주요 기능인 **여행지 선택 기능**이 제공됩니다.  
사용자는 **주소, 관광지 유형, 키워드** 세 가지 입력을 통해 원하는 여행 목적지나 정보를 필터링할 수 있습니다.  
값을 입력하고 검색 버튼을 클릭하면 해당 전국 관광지 정보 화면으로 이동하며, 입력한 값으로 필터링된 여행지를 보여줍니다.  

![메인화면_로그인전](/uploads/ba473f78b6edf375fa7f15ec642269cd/메인화면_로그인전.PNG)  

## 2. 관광지  - 전국 관광지 정보
전국 관광지 정보 화면에서는 사용자가 **검색할 지역, 관광지 유형, 키워드**를 입력하고 검색 버튼을 클릭하면 검색 결과가 화면 하단에 테이블 형태로 나타납니다.  
이때, 검색 결과 리스트는 **지도에 마커**로도 표시됩니다.  
사용자는 리스트 요소를 클릭하면 해당 위치의 마커로 이동할 수 있습니다.  

![map](/uploads/ffda48600b1be6d9b08535a4cd685ce9/map.png)

## 3. 로그인
로그인 하기 전 화면에서는 로그인과 회원가입, 비밀번호 수정을 할 수 있습니다.  

![메인화면_로그인전](/uploads/ba473f78b6edf375fa7f15ec642269cd/메인화면_로그인전.PNG)  
  

로그인 한 후의 화면에서는 로그인 탭이 없어지고 내 정보를 확인/수정 버튼과 로그아웃 버튼이 활성화 됩니다.  

![메인_로그인후](/uploads/addd42b22a8ae5588971089146504f72/메인_로그인후.PNG)

## 4. 회원가입
회원가입 버튼을 클릭하면 회원가입 모달창이 표시되며, 해당 모달창에서 필요한 정보를 입력하여 회원가입을 할 수 있습니다.  

![회원가입](/uploads/a60fddf4b2946bb82c10928f36a3919b/회원가입.png)  


## 5. 비밀번호 수정
아이디와 이메일을 입력하고 회원 정보와 일치한다면 해당 회원의 비밀번호를 수정할 수 있는 입력 칸이 활성화되고 비밀번호 수정을 할 수 있습니다.  

![비밀번호수정1](/uploads/06b530540e2d3fb5e8bb4b3529777a06/비밀번호수정1.PNG)
![비밀번호수정2](/uploads/d371518e29f7334782311a304539d074/비밀번호수정2.PNG)

## 6. 회원정보 확인/수정
로그인한 사용자는 자신의 정보를 확인하고 수정할 수 있습니다.  

![내정보_확인_수정](/uploads/50c54580239bc16ca2c13e2e2a0b4aa0/내정보_확인_수정.PNG)  
