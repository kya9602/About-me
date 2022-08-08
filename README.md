## 🙌 About  ME를 소개합니다.

![image](https://user-images.githubusercontent.com/85295433/183332086-09345165-70ee-45ab-b759-fb4428e4a926.png)

## ❓ About  ME 가 뭐예요?   
- 개발자의 성장기를 시각화 하여 담아내는 포트폴리오 웹 사이트입니다.
- 거쳐온 프로젝트, 커리어들을 통해 발전해 나가는 우리의 모습을 한 눈에 볼 수 있습니다.
- edit 버튼을 통해 내정보, 보유스킬, 커리어, 프로젝트 등을 깔끔하게 정리해줘요.


## 🛠 구현중인 기능
<s>1. root 페이지 구현 (완)
- 검색창 연결</s>
- 내 페이지가기 버튼 추가 및 연결

<s>2. 로그인 / 회원가입 페이지 구현 (완)
- 로그인
- 회원가입

3. 메인 페이지 구현 (완)
- Identify 연결
- 인적사항
- 보유기술
- 프로젝트
- Footer
</s>

4. 어드민 페이지 구현
- <s>로그아웃(완)
- 인적사항 edit 버튼 활성화 및 수정 반영</s>
- 보유기술 edit 버튼 활성화 및 수정 반영
- 프로젝트 edit 버튼 활성화 및 수정 반영


<s>5. 메뉴 페이지 구현 (완)
- Nav 버튼 구현완료 </s>


## 🚗 사용된 기술.
- python , js , html , css
- pymongo , flask , jinja2 , pyJWT


## 🙋‍♀️ Trouble Shooting
1. -1 Career Section image 가운데 정렬안됨
- width height position margin 등등 온갖 것을 손대보고
- 마무리는 margin : auto auto; 였음


1. -2 image 테두리 둥글게 나오면서 이미지가 조금 짤림
- 숨어있던 rounded-circle 찾아서 해결


2. 온클릭 이벤트 실행안됨
- js 링크 추가해서 해결


3. modal 창 is-active 문제
- bulma css 긁어온것이라 bulma script 추가해서 해결


4. font 겹침 문제
- core theme css 위에 bulma css를 추가해서 해결 (순서배치문제) 


5. 회원정보 수정시 모두가 수정버튼을 볼 수 있었던 문제.
- JWT 토큰을 이용해 서버에 유저 정보가 있다면 클라이언트 ID를 저장하고 jinja2를 이용해 정보를 넘겨주어 이슈 해결


6. 파일 추합을 하는경우 변수명이 달랐고, 팀 개개인의 개발 환경이 다른 문제
- git 을 앞으로는 !꼭! 제일먼저 설정하자


7. token = jwt.encode(payload, SECRET_KEY, algorithm='HS256').decode('utf-8')
- 로그인이 안되는문제 : .decode~ 이부분 삭제해서 해결


<details><summary> P.S </summary>

 ![image](https://user-images.githubusercontent.com/85295433/183233382-373f77b6-19ba-47ed-a2f7-fd7c776ae03e.png) 
 
 - 이노베이션캠프(강원) 첫주 5조 
 - Team Innovation Camp(Gangwon). First week group 5 

</details>
