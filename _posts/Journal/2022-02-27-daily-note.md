# Sunday, February 27, 2022

## TIL
[[Journal]] [[Computer]]
만약 zsh가 느려진다면, `zsh -xv` 명령어로 프로파일링 해보자.
열심히 엔터를 쳐보며 어디가 느려지는지 확인해보니, pyenv 설정한 부분에서 약간씩 렉걸리는 것 같았다.
단순히 eval 명령어를 사용했을 뿐인데... 음... 쉘에서 명령어를 실행하는 명령어라 느려지게 되는건가?
아무튼 모두 주석처리하고 나중에 pyenv 사용할 일이 있을 때 꺼내서 써야겠다.

react-router-dom에서 Link 컴포넌트를 사용하면, 링크 이동 시, 모든 페이지가 재로딩되는 것을 막아준다. html의 `<a href=""></a>`를 이용하는 것보다 훨씬 낫다!

react-router-dom v.6은 5.3v와 다르게 Switch를 사용하지 않는다. 이제 그 역학은 `<Routes>`가 대신할 것이며, 또한 Route 태그의 exact 속성도 더 이상 쓰이지 않을 것이다. 왜냐하면 Routes가 알아서 최적의 경로배정을 해주기 때문에, Switch에서 생기는 문제들을 막아준다.

리액트에서 컴포넌트란, 템플릿 이상의 기능을 수행하며, 데이터를 UI로 만들어 주는 기능을 한다. 컴포넌트란 기능을 단위별로 캡슐화한 단위를 말한다. 컴포넌트는 독립적이며, 재사용 가능하게 만든 부품 조각들을 말한다. 리액트로 만들어진 홈페이지는 컴포넌트의 조합이다.

react-router-dom에서 useParams를 이용하면, react-router에서 설정한 동적 파라미터값을 가질 수 있다.