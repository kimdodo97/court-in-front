<template>
  <header>
    <div class="container">
      <nav class="nav-container">
        <div class="user-menu">
          <div class="left-nav-box">
            <div class="global-nav">
              <img
                  src="	https://d31wz4d3hgve8q.cloudfront.net/static/img/ic_hamburger.svg"
              />
            </div>
            <a href="/">
              <img src="@/assets/imgs/main-logo.png" />
            </a>
          </div>
          <div class="right-nav-box">
            <div class="show-search"></div>
            <a href="">검색</a>
            <a href="">마이페이지</a>
          </div>
        </div>
      </nav>

      <nav class="explore-container">
        <div class="explore-wrapper">
          <div class="explore-item">
            <a href="#경기">소셜 매치</a>
            <a href="#team">팀<span class="is-new">new</span></a>
            <a href="#포스팅">구장 예약</a>
            <a href="">배구 지식</a>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>


<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
@import url("@/common/css/header-menu.css");
@import url("@/common/css/header-nav.css");

.container {
  max-width: 1024px;
  margin: 0 auto;
  padding: 0 20px; /* 좌우 패딩을 추가하여 좌측 정렬 */
  box-sizing: border-box; /* 패딩과 테두리를 포함하여 박스 크기를 계산 */
}

a {
  font-family: "Pretendard-Regular", sans-serif;
  font-size: 12px;
  font-weight: 400;
  line-height: 140%;
  color: rgba(0, 0, 0, 0.95); /* 전역으로 폰트 적용 */
}
</style>