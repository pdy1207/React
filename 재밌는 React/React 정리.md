# React

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
     -  중요한 데이터는 state로 저장해서 쓰세요
