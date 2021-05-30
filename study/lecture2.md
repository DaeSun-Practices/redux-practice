# store
정보가 저장되는 곳.  
state라는 곳에 직접 저장이 된다.  
다만 다이렉트로 접속이 불가능하다.

# reducer
state를 수정하는 함수.  
reducer를 만드는 일이 중요하다.  

# render
리덕스와 상관없이 UI를 만들어준다.  
개발자가 짤 코드이다.

# getState
데이터를 가져오는 함수이다.

# subscribe
state의 값이 바뀔 때마다 render함수가 호출된다.

# dispatch
객체를 전송받는다.  
1. reducer를 호출한다 : 현재의 state값과 action이라는 객체를 reducer에게 전달한다.
2. subscribe를 호출한다. : reducer의 호출이 끝나면 새로운 state값을 return받아서 subscribe에 전달한다.  
   -> UI가 바뀐다.