<template>
  <article>
    <div class="detail-404">
      <h2 class="detail-404-heading">404</h2>
      <router-link class="detail_btn" to="/home">Back Home</router-link>
    </div>
  </article>
</template>

<style scoped>
article {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.detail-404 {
  text-align: center;
  height: 100%;
  background-color: #f0f0f0;
}
.detail-404-heading {
  font-size: 10rem;
  letter-spacing: .15em;
}
.detail_btn {
  display: inline-block;
  width: 130px;
  background: #384f66;
  color: #fff;
  font-size: 1.4rem;
  text-align: center;
  text-decoration: none;
  line-height: 32px;
  height: 32px;
  border-radius: 2px;
  box-shadow: 0 1px 1px rgba(0,0,0,.45), inset 0 1px 0 rgba(200,200,200,.45);
  transition: background .65s ease-in-out;
  letter-spacing: .075em;
}
.detail_btn:hover {
  background: #456a8e;
}
</style>
