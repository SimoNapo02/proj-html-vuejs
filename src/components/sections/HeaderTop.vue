<template>
  <div class="info-header">
    <div class="row">
      <div class="col-sx">
        <p>
          <i class="fa-solid fa-clock"></i> Open Hours: Mon - Sat - 9:00 -18:00
        </p>
      </div>
      <div class="row col-dx">
        <div><i class="fa-solid fa-phone"></i> +1 (305) 1234-5678</div>
        <div><i class="fa-solid fa-envelope"></i> hello@example.com</div>
        <i class="fa-brands fa-facebook-f"></i>
        <i class="fa-brands fa-twitter"></i>
        <i class="fa-brands fa-linkedin-in"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderTop",
};
</script>

<style lang="scss" scoped>
.info-header {
  height: 3.125rem;
  background-color: #21333e;
  color: #c0c3d0;
  .row {
    display: flex;
    height: 3.125rem;
    flex-direction: row;
  }

  .col-dx {
    width: 500px;
    margin-left: 43.75rem;
    margin-top: 0.625rem;
    justify-content: space-between;
  }
  .col-sx {
    margin-top: 0.625rem;
  }
}
</style>
