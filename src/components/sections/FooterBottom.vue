<template>
  <div class="footer-bottom">
    <div class="container">
      <div class="row">
        <div class="col">
          <p>Enjoy the low price. We are tracking any intencion of piracy</p>
        </div>
        <div class="col">
          <p>©2020 NEXGEN is Proudly Powered by <span>Codings</span>.</p>
        </div>
      </div>
    </div>
    <span class="icon"
      ><font-awesome-icon icon="fa-solid fa-arrow-up" class="align-self-center"
    /></span>
  </div>
</template>

<script>
export default {
  name: "FooterBottom",
};
</script>

<style lang="scss" scoped>
.footer-bottom {
  max-width: 1516px;
  padding: 1.875rem 0;
  background-color: #0d0d11;
  color: #c0c3d0;
  display: flex;
  flex-direction: row;
  .col {
    p {
      margin-right: -1.5625rem;
    }
    span {
      color: #0b7283;
    }
  }
  .icon {
    color: #0c1b1f;
    font-size: 1.25rem;
    background-color: #29292d;
    padding: 0.3125rem 0.8125rem;
    border-radius: 50%;
    margin-right: 1.5625rem;
  }
}
</style>
