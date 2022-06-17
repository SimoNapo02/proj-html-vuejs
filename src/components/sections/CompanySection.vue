<template>
  <div class="company">
    <div class="comp-top">
      <h6>ABOUT THE NETWORK</h6>
      <h1>
        <span
          style="
            background-color: #0e272d;
            padding-left: 5px;
            padding-right: 5px;
          "
          >The</span
        >
        Company
      </h1>
      <p>
        With all of this expertise and capability comes an unrivaled commitment
        to customer service
      </p>
    </div>
    <div class="comp-stats">
      <div class="leadership">
        <div class="number">0%</div>
        <div class="info">
          <h3>Leadership</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
        </div>
      </div>
      <div class="psychology">
        <div class="number">0%</div>
        <div class="info">
          <h3>Psychology</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
        </div>
      </div>
      <div class="flexibility">
        <div class="number">1%</div>
        <div class="info">
          <h3>Flexibility</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
        </div>
      </div>
    </div>
    <img class="image" src="../../assets/img/about-5.jpg" />
  </div>
</template>

<script>
export default {
  name: "CompanySection",
};
</script>

<style lang="scss" scoped>
.company {
  display: flex;
  flex-direction: column;
  background-color: var(--jumbo-color-bg);
  color: white;
  width: 43.75rem;
  height: 37.5rem;
  padding-top: 4.6875rem;
}

.leadership,
.psychology,
.flexibility {
  display: flex;
  float: right;
  padding-top: 1.25rem;
  padding-bottom: 1.25rem;
  width: 25rem;
}
.comp-stats {
  margin-top: 2.5rem;
}
.number {
  margin-right: 1.875rem;
  border-radius: 50%;
  width: 4.375rem;
  height: 4.375rem;
  padding: 1rem;
  border: 6px solid #666;
  color: white;
  text-align: center;
}
.comp-top {
  margin-left: 18.75rem;
}
h6 {
  color: var(--third-text-color);
}
.comp-stats p {
  padding-top: 0.625rem;
  padding-bottom: 0.625rem;
}
.image {
  position: absolute;
  width: 51.1875rem;
  height: 37.5rem;
  margin-left: 43.75rem;
  margin-top: -4.6875rem;
}
</style>
