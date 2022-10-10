# React

 * ***우선 react 를 시작하려면 기초 html, css 가 필요하다 + JavaScript... 왜?***
 * ***이유는 간단하다 react에서 JSX라는 문법을 쓰는데 이게 JSX 자바스크립트 와 html 한번에 합쳐 놓은것 같은 문법 이기 때문***


 - 터미널에 뜨는 warning 

 ![3](https://user-images.githubusercontent.com/110442250/194712722-875c9717-bf04-4b8b-a3e2-97e76a11baeb.jpg)

eslint가 잡아주는 문법 체크사항 사진처럼 저게 뜨는게 싫다 !! 

      그러면  /* eslint-disable */ 맨위에 적어주자

 - 수정할 데이터를 하려면??
   - 수정된 [데이터] 를만듭니다
      - 근데 state를 deep capy해서 수정하세요. 
      - state는 직접 건들지마셈 deep copy해서 그걸 건들자.


 - state에 데이터 저장해놓는 이유 
     -  state는 변경되면 html이 자동으로 재렌더링이 됨.
     -  새로고침 없이 스무스하게 변경 자주 바뀌고 
     -  중요한 데이터는 state로 저장해서 쓰세요.

### html 을 한단어로 줄여서 쓸 수 있는 방법 : 리엑트의 component 문법

 - Component만드는 법</br>
 - 단점? state 슬때 복잡해짐</br> 
 
       어떤걸 Component 만드는게 좋을까?
       반복 출현하는 html 덩어리들
       자주 변경되는 html ui 들
       다른 페이지 만들 때도 컴포넌트로 만듦
       

![3](https://user-images.githubusercontent.com/110442250/194856440-5ec2c30d-8162-4e60-a27f-4ded67b5fe18.jpg)
