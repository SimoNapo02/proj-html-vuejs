<template>
  <div class="service">
    <div class="row">
      <div class="info">
        <h6>OUR BUSINESS AREA</h6>
        <h1>Logistic Services</h1>
        <p>
          We are leaders in providing logistics Services with a set of cutting
          edge technologies and a team of experienced and renowed professionals.
        </p>

        <div class="key">
          <p>Tradition</p>
          <p>Quality</p>
          <p>Security</p>
        </div>
        <div class="green-touch">READ MORE</div>
      </div>
      <div class="picture">
        <div
          class="tech"
          style="padding: 50px; background-color: white; width: 350px"
        >
          <img style="width: 250px" src="../../assets/img/gallery-3.jpg" />
          <h3>Technology</h3>
          <p>
            Focused on developing technology solutions adapted to our client
            needs.
          </p>
        </div>
        <div
          class="transport"
          style="padding: 50px; background-color: white; width: 350px"
        >
          <img style="width: 250px" src="../../assets/img/gallery-5.jpg" />
          <h3>Transport</h3>
          <p>
            We develop operational strategies to improve logistical efficiency.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServiceSec",
};
</script>

<style lang="scss" scoped>
.service {
  background-color: var(--jumbo-green-bg);
  padding-top: 4.6875rem;
  padding-bottom: 4.6875rem;

  .row {
    display: flex;
    flex-direction: row;
  }
  .info {
    display: flex;
    flex-direction: column;
    width: 18.75rem;
    margin-left: 1.25rem;

    .key {
      display: flex;
      flex-direction: row;
      justify-content: space-evenly;

      padding-bottom: 0.625rem;

      p {
        color: var(--third-text-color);
        background-color: var(--words-color-bg);
        padding: 0.4375rem;
        border-radius: 4px;
      }
    }
    h6 {
      padding-bottom: 0.9375rem;
      color: var(--third-text-color);
    }
    h1 {
      padding-bottom: 1.25rem;
      font-size: 2.5rem;
    }
    p {
      padding-bottom: 0.9375rem;
    }
  }
  .picture {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
  }
  .tech {
    margin-left: 12.5rem;
    margin-right: 3.125rem;
    padding-right: 3.125rem;
  }
  .green-touch {
    background-color: var(--button-color);
    padding-top: 0.3125rem;
    padding-bottom: 0.3125rem;
    text-align: center;
    width: 7.8125rem;
    margin-left: 4.375rem;
    color: white;
  }

  h3 {
    padding-top: 0.625rem;
    padding-bottom: 0.625rem;
  }
}
</style>
