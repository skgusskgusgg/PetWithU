![header](https://capsule-render.vercel.app/api?type=Rect&color=a41523&fontColor=f3eadd&height=300&section=header&text=PETWITHU&fontSize=120)

- 인테리어 제품을 커뮤니티 활성화를 이용하여 활발하게 판매하고있는 사이트 (오늘의 집)을 모델링한 프로젝트입니다.
- petwithU는 반려동물을 사랑하는 사람들이 모여 소통하고 상품을 판매하는 사이트입니다.

# 개발 기간

- 2023.1.30 - 2023.2.10 (2주)

# 개발 인원 및 파트

## FE

|개발자                 |파트                |
|---------------------|-------------------|
|강서윤(Project Manager)| 산책로페이지         |
|권나현                 |커뮤니티 글쓰기 페이지<br>상품디테일페이지<br>장바구니페이지|
|배경민                 |메인페이지,피드페이지,네브|

## BE

|개발자                  |파트               |
|----------------------|------------------|
|최민주(Product Manager) |DB,Node.js,Express|

# 기술 스텍

### 프론트엔드

|JavaScript|React|Styled<br>Component|esLint|Prettier|
|----------|------|---------------|-------|--------|
|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="65" height="65" /></div>|<img height='80' src="https://raw.githubusercontent.com/styled-components/brand/master/styled-components.png" />|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/eslint-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/prettier-icon.svg" alt="icon" width="65" height="65" /></div>

### 백엔드

|JavaScript|Node.js|MySql|Rest|
|----------|-------|-----|-----|
|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="65" height="65" /></div>|

# 서비스 소개

- 게시글을 작성하여 하나의 피드를 만들고 작성할 때 사이트에서 구매한 제품을 태그하여 다른 유저가 쉽게 상품에 접근 할 수 있습니다.
- 유저들이 가볼만한 산책로를 모아서 지역별로 나눠 두어 집근처 산책로를 빠르게 접근 할 수 있습니다.
- 지도api 기능을 통해 좌표로 어느위치인지 표시해 줍니다.
- 유저가 좋아요를 누르고 스크랩한 피드와 산책로를 스크랩 페이지에 모아서 볼 수 있도록 하여 유저의 히스토리를 기록할 수 있습니다.
- 소셜 로그인기능을 통해 번거로운 회원가입 절차를 생략하여 사용자의 경험을 높힐 수 있습니다.

# 협업 툴

#### api 관리 <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"> - BE
#### 스케쥴 및 기능구현 티켓 관리 <img src="https://img.shields.io/badge/trello-0052CC?style=for-the-badge&logo=trello&logoColor=White"> - FE & BE
#### 협업 소통 및 자료, 정보 공유 <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=trello&logoColor=White"> - FE & BE

# 구현기능

### 상품 디테일 페이지

1) 사용자가 원하는 상품에 대한 상세를 나타내줌
2) 사용자가 구매하고싶은 만큼 상품의 수량을 증감 할 수 있음
3) 사용자가 바로 구매하지 않고 장바구니를 클릭하면 장바구니 페이지로 상품을 넘겨줌

### 장바구니 페이지

1) 사용자가 장바구니에 넣어 놨던 상품의 리스트를 한눈에 보기 쉽게 출력
2) 사용자가 원하는 상품의 체크박스를 클릭시 해당하는 상품만 구매 가능하게 함
3) 사용자가 장바구니 내에서 상품을 추가 or 삭제할 수 있으며, 선택된 상품의 전체값을 한눈에 볼 수 있음

### 커뮤니티 글쓰기 페이지

1) createObjectURl() 메서드를 이용하여 사용자가 올리고싶은 이미지 미리보기
2) 사용자가 이미지를 클릭했을때, 원하는 지점에 등록하고싶은 아이템을 담을 아이콘 생성
3) 사용자가 선택한 아이콘에 검색기능을 추가하여 사용자가 다른 사용자에게 추천하고 싶은 아이템을 선택
4) 사용자가 전하고 싶은 카테고리, 메세지, 해시태그를 담을 수 있는 input창 생성
5) 하나의 게시글에 하나의 이미지와 메세지만 올리는 것이 아닌, 사용자가 원한다면 하나의 게시글에 여러 이미지와 메세지들을 담을 수 있게 추가 기능 생성
6) new formdata()를 이용하여 서버에 업로드한 이미지 저장

