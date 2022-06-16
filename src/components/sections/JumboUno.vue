<template>
  <div class="gradient">
    <div class="hero">
      <div class="Logic">
        <h1 class="title">
          Logistics that go further
          <div class="mark"></div>
        </h1>
        <p>
          For 20 years working with the most innovative in the field of
          transport
        </p>
      </div>
      <div class="row">
        <div class="green-touch">GET IN TOUCH</div>
        <div class="read-more">READ MORE</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "JumboUno",
};
</script>

<style lang="scss" scoped>
.hero {
  background: url("../../assets/img/jumbo.jpg");
  height: 37.5rem;
  color: var(--primary-text-color);

  .Logic {
    float: right;
    margin-top: 6.25rem;
    width: 18.75rem;
    margin-right: 18.75rem;

    .title {
      font-size: 3.125rem;
      position: relative;
    }

    .mark {
      display: none;
      position: absolute;
      background-color: var(--button-color);
      opacity: 0.5;
      width: 13.125rem;
      height: 1.5625rem;
      margin-top: -4.375rem;
    }
  }

  .row {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 18.75rem;
    float: right;
    margin-top: 25rem;
    margin-right: -15.625rem;

    .green-touch {
      background-color: var(--button-color);
      padding-left: 0.9375rem;
      padding-right: 0.9375rem;
      padding-top: 0.3125rem;
      padding-bottom: 0.3125rem;
      text-align: center;
    }

    .read-more {
      border: 0.1875rem solid var(--button-color);
      text-align: center;
      padding-left: 0.9375rem;
      padding-right: 0.9375rem;
      padding-top: 0.3125rem;
      padding-bottom: 0.3125rem;
    }
  }
}
</style>
