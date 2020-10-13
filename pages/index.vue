<template>
  <div class="container">
    <div>
      <h1 class="title">
        <img src="~/assets/img/logo.svg" alt="cross chop クロスチョップ" />
      </h1>
      <p class="subtitle">We know HTML, CSS and Javascript.</p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  // text-align: center;
}
.title {
  img {
    display: block;
    width: 260px;
    margin: 0 auto;
    transform: translate(5px, 0);
  }
}

.subtitle {
  font-weight: 500;
  font-size: 11px;
  letter-spacing: 0.03em;
  color: #000;
  margin: 0 0 0 -5px;
  text-align: center;
  // word-spacing: 5px;
  // padding-bottom: 15px;
}
h2 {
  font-size: 18px;
  text-align: center;
  margin-top: 20px;
}
ul {
  display: flex;
  // background: red;
  padding: 0;
  margin: 0;
  justify-content: center;
  li {
    // background: blue;
    list-style: none;
    margin: 0 10px;
    width: 50%;
    &:first-child {
      text-align: right;
    }
    &:last-child {
      text-align: left;
    }
  }
}

.note {
  margin-top: 1em;
}

.links {
  padding-top: 15px;
}
</style>
