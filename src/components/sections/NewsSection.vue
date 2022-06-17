<template>
  <div class="news container">
    <div class="top">
      <h6>OUR EDITORIAL CONTENT</h6>
      <h1>Latest News</h1>

      <span>
        Every week we publish content about what is best in the business world

        <div class="green-touch">SEE ALL</div>
      </span>
    </div>
    <div class="bot">
      <div class="uno">
        <img
          src="../../assets/img/news-1.jpg"
          style="filter: brightness(50%); width: 400px"
        />
        <div class="text">Increasing creativity is possible for everyone</div>
      </div>
      <div class="due">
        <img
          src="../../assets/img/news-2.jpg"
          style="filter: brightness(50%); width: 400px"
        />
        <div class="text">Increasing creativity is possible for everyone</div>
      </div>
      <div class="tre">
        <img
          src="../../assets/img/news-3.jpg"
          style="filter: brightness(50%); width: 400px"
        />
        <div class="text">Increasing creativity is possible for everyone</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewsSection",
};
</script>

<style lang="scss" scoped>
.news {
  padding-top: 4.6875rem;
  padding-bottom: 4.6875rem;
}
h6 {
  color: var(--third-text-color);
  padding-bottom: 0.9375rem;
}
span {
  display: flex;
  flex-direction: row;
  padding-top: 0.9375rem;
  padding-bottom: 0.9375rem;

  .green-touch {
    background-color: var(--button-color);
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    padding-top: 0.3125rem;
    padding-bottom: 0.3125rem;
    text-align: center;
    color: white;
    margin-left: 40.625rem;
  }
}
.bot {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.uno,
.due,
.tre {
  position: relative;
  text-align: center;
}
.text {
  position: absolute;
  bottom: 8px;
  color: white;
  font-size: 24px;
  padding-bottom: 0.9375rem;
}
</style>
