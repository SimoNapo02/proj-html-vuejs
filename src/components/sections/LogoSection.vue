<template>
  <div class="logo">
    <img src="../../assets/img/logo-5.png" />
    <img src="../../assets/img/logo-1.png" />
    <img src="../../assets/img/logo-2.png" />
    <img src="../../assets/img/logo-3.png" />
    <img src="../../assets/img/logo-4.png" />
    <img src="../../assets/img/logo-5.png" />
  </div>
</template>

<script>
export default {
  name: "LogoSection",
};
</script>

<style lang="scss" scoped>
.logo {
  display: flex;
  justify-content: space-between;
  padding-top: 6.25rem;
  padding-bottom: 6.25rem;
  background-color: var(--words-color-bg);

  img {
    width: 9.375rem;
    height: 3.125rem;
    filter: brightness(300%);
  }
}
</style>
