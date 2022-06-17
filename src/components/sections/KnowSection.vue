<template>
  <div class="know">
    <div class="col-sx">
      <h6>NEWSLETTER</h6>
      <h1><span>Know</span> First</h1>
      <p>
        Follow closely and recieve content about our company and the news of the
        current market
      </p>
    </div>
    <div class="col-dx">
      <input type="text" placeholder="Name" />

      <input type="text" placeholder="Email" />
      <div class="green-touch">SUBSCRIBE</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "KnowSection",
};
</script>

<style lang="scss" scoped>
.know {
  background-image: url("../../assets/img/bg-1.jpg");
  display: flex;
  flex-direction: row;
  color: white;
  justify-content: center;
  height: 25rem;
  padding-top: 9.375rem;

  .col-sx {
    display: flex;
    flex-direction: column;
    width: 31.25rem;
    padding-right: 1.25rem;
    h1 {
      padding-top: 0.9375rem;
      padding-bottom: 0.9375rem;
    }
  }
  .col-dx {
    display: flex;
    flex-direction: column;
    width: 25rem;

    input {
      background-color: rgba(255, 255, 255, 0.574);
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      box-sizing: border-box;
      border-radius: 0.25rem;
      border: none;
      color: white;
    }
  }
  .green-touch {
    background-color: var(--button-color);
    padding-left: 0.9375rem;
    padding-right: 0.9375rem;
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    width: 6.875rem;
    border-radius: 0.25rem;
  }
  span {
    background-color: #173338cc;
    padding: 0.3125rem;
  }
}
</style>
