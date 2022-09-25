# Next.js 경험을위한 공식문서 프로젝트 

<br/>

> ## Pre-rendaring 

 Next.js 는 모든 페이지를 pre-render 한다 
 pre-render : 페이지를 렌더링 하기위한 HTML 을 클라이언트 단에서 처리하기이전에, 미리 생성하는것 

<br/>

> ## Data Feching

 react 에선 데이터를 가져올때 useEffect 를 주로사용한다
 Nnxt.js 에선 데이터를 가져오기 위해 여러 방법을 사용한다

#### 1. getStaticProps :
 build 시에 데이터를 불러옵니다

#### 2. getStaticPaths :
 pre-render 시 특정한 동적 라우팅을 구현 합니다 

#### 3. getServerSideProps:
 SSR으로 요청이 있을떄 데이터를 불러옵니다