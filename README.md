# 2차 프로젝트 4팀 FrontEnd 소개

<a href="http://www.ggsd.ml:8000/"> 사이트 바로가기 </a>


- 숨고 클론 프로젝트

- 해당페이지를 다시 기획하여 숨은 고수를 찾아주는 페이지가 아닌
  개발자들끼리 프로젝트를 매칭해주는 페이지로 기획 변경해보았습니다.

# 개발 인원 및 기간

- 개발기간 : 2022/05/09 ~ 2022/05/20
- 개발인원 : 
 
  프론트엔드 - 이희준, 최승이, 이하영, 정덕우  |  백엔드 - 지기성,임수연

# 사용기술

- FrontEnd : React.js, React Router, Style Component, React Library
- 협업 툴 : Git, Trello, Slack, Notion

# 구현기능

- 소셜 로그인 기능 (카카오)
- 메인페이지 : 캐러셀
- 리스트페이지 : 필터링 기능 , 무한스크롤 기능
- 프로젝트 생성페이지 : 폼데이터 전송 기능
- 마이페이지 : 사진 백엔드로 전송 및 백엔드에서 받아서 활용

# Reference

- 이 프로젝트는 숨고 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.


# 내가 맡은 부분

## 프로젝트 생성 페이지
![프로젝크 생성](https://user-images.githubusercontent.com/93138130/169648176-81b3a451-f041-4caa-abb3-6ec86eef8ea6.gif)

1. formData 사용하여 이미지 S3에 업로드
2. 이미지 프리뷰
3. async/await 사용하여 이미지 업로드 -> 프로젝트 생성완료 한번에 하여 계속 이미지를 저장하지 않고 마지막 이미지만 전달함으로 효율을 높임
4. 프로젝트 생성 내용 하나의 스테이트로 백엔드에 전달
5. 마이페이지의 내가 생성한 프로젝트에 보여짐

## 프로젝트 디테일 페이지
![프로젝트 디테일](https://user-images.githubusercontent.com/93138130/169648187-edaa80dc-be69-4428-96a4-00436ecdd87b.gif)

1. useParams() 사용하여 프로젝트 내용 받아옴
2. 프로젝트 생성 시 내 포트폴리오 공개 여부에 따라 프로젝트 생성자 포트폴리오 다운로드 버튼 유/무 변화
3. 포트폴리오 파일 다운로드 가능
4. 쪼인 모달 클릭 시 유저 정보 + 선택 내용 백엔드에 전달
5. 마이페이지로 자동이동 되며 내가 요청한 프로젝트에 해당 프로젝트 보여짐


## 느낀점
기획할 때 클론으로 진행하지 않아 스타일을 우리끼리 맞춰가면서 진행하였고, 데이터 뿐만아니라 많은 소통을 진행하여서 만족스러웠다.

스타일컴포넌트를 처음 하며 첫날은 멘붕이었으나 쓰다보니 prop을 바로 사용가능하여 편한 느낌도 있었다.

또한 백엔드와 통신을 경험하면서 이맛에 개발을 하는구나 많이 느낀 시간이었다.

개인적으로는 휼륭한 팀원들과 하면서 진행 속도에 구애받지 않고 내가 맡은 기능 하나하나 코드 한줄씩 다 이해하면서 작업했었다.
그리고 formData로 S3업로드 해본 것, async/await의 활용을 잘 사용했던것 같아 얻어가는 게 많았던 프로젝트였다.


