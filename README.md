# week06 TODO 리스트

### TODO 할일
## 필수
- [x] 메인 페이지 (index.html)
- [x] 로그인 페이지 (login.html) 
- [x] re회원가입 페이지(join.html) 다시 만들기 - 기능 만들어 보기 (모두의 책 리뷰 참고) ★★★★★
- [x] 코드, 학습목표, 대제목 등의 관리자 등록 페이지(ad_registerContent.html) [셀렉트] ★★★★★
       -코드 인풋박스 쓰고 대제목 누르면 코드와 대제목 쓸 수 있는 인풋박스, 소제목 누르면 코드와 대제목이 셀렉트로 된 소제목에 글 넣을 수 있는 인풋박스  
       -기능은 튜터님하고 !!
- [x] 등록된 회원 리스트 페이지 ★★
- [x] 개별 학습내용 등록 페이지 (ad_registerObjStu.html) ★★★
- [ ] [이전, 다음] 넣기 [!! 10페이지 정도만 보이게, 이전 다음 연결, 내림 차순 ](member_list.html)
- [x] 회원의 마이페이지(mypage.html)[학습내용-날짜, 제목 썸네일 리스트로 정렬/ 내용 드롭다운]


## 2020.11.15 해야 할일
- [ ] 도메인 구매
- [ ] aws 서버 연결해보기
- [ ] 학습목표 불러와서 디비에 
- [ ] 로그인



## 선택
- [ ] 학생별 학습 목표 보기
- [ ] 회원 학습 리스트[pagination] (my_list.html)
- [ ] 회원의 마이페이지
- [ ] ID, PW 찾기
- [ ] 내 정보 보기 페이지
- [ ] 내 정보 수정

- [x] 아님: 다시 재구성 할 것학습등록페이지 : 관리자가 학생에 따라 그날 학습 등록하는 페이지 [셀렉트] (wr_board.html)


### ===================================================
*부트스트랩 참고
 페이징 : https://umg99.tistory.com/23
 달력 :https://getbootstrap.com/docs/4.5/content/reboot/?optionsRadios=option1
       https://jsonobject.tistory.com/181
       https://programmer93.tistory.com/5
       https://stackoverrun.com/ko/q/3603559
 ad_registerContent.html : (JavaScript behavior) https://getbootstrap.com/docs/4.5/components/list-group/
                            (vertical pills)  https://getbootstrap.com/docs/4.5/components/navs/
 
### 프로젝트
**공통, html**
* header, footer, menu - 나눠서 import 하는 방법 찾기 ☆
* 검색창

**메인**
1. 레이아웃 1차
   1) - [x] 메뉴바 ☆
   2) 메인 슬라이드 
   3) 컨텐츠
       - api 활용 ☆
       - 유투브 연동 화면 컨텐츠 ☆ (용량 차지?)
       - 기타


**로그인 및 회원가입/ myPage**
1. 로그인 
- [x] 로그인 페이지 만들기★
- [ ] ID, PW 찾기

2. 회원가입
- [▲] 회원가입 페이지 만들기 ★ 
   아이디(중복여부)
   패스워드, 패스워드 확인
   이메일(유효성 검사)
   휴대폰
   성별
   기타 동의 여부
   
   *참고 사이트
   https://huskdoll.tistory.com/104  ---퍼와서 고칠 것
   
   주소 api 사용  
   https://m.blog.naver.com/PostView.nhn?blogId=elriot&logNo=221407141213&proxyReferer=https:%2F%2Fwww.google.com%2F
   부트스트랩  
   (Form row)  https://getbootstrap.com/docs/4.5/components/forms/
   (Forms)비밀번호 찾기, 회원가입 https://getbootstrap.com/docs/4.5/components/dropdowns/

3. Mypage(사용자)
- [ ] 내 스터디 내역 확인 ★
     1) 게시판 형태 작은 썸네일 리스트 ☆
         - 클릭시 내용 확인
            (Accordion example) 참고 https://getbootstrap.com/docs/4.5/components/collapse/
         - 한페이지 10개 목록 볼 수 있는 페이지 (이전, 다음 페이지) 
- [ ] 내 정보 보기 페이지 ☆
- [ ] 내 정보 수정
- [ ] 회원의 마이페이지(mypage.html) -프린트 설정, jpg 이미지로 다운로드



**게시판(관리자)**
1. 글 등록 
- [ ] 게시판 페이지 만들기 ★
- [ ] 드롭다운 목록 만들기-사용자 ID(이름), 제목, 목표, 날짜 추가★  
        https://getbootstrap.com/docs/4.5/components/dropdowns/
- [ ] 내용 작성 textarea & 사진, 파일 첨부 ★
       (Supported elements) https://getbootstrap.com/docs/4.5/components/forms/
   
2. 회원 리스트 및 회원관리(수정)
- [ ] 회원리스트 페이지 (이전, 다음) ★  
     (Working with icons) https://getbootstrap.com/docs/4.5/components/pagination/
     (아이디, pw, 이름, 이메일, 휴대폰, 성별, 주소)
- [ ] 회원 선택시 스터디 내역 확인(mypage와 같은 페이지)
   

 
