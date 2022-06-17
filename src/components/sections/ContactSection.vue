<template>
  <div class="contact">
    <div class="col-sx">
      <div class="top">
        <h6>SEND A MESSAGE</h6>
        <h1>Get in <span class="touch">Touch</span></h1>
        <p>we will respond to your message as soon as possible</p>
      </div>
      <div class="bot">
        <div class="info-uno">
          <input type="text" placeholder="Name" />
          <input type="text" placeholder="Email" />
        </div>
        <div class="info-due">
          <input type="text" placeholder="Phone" />
          <input type="text" placeholder="More info" />
        </div>
        <input class="big" type="text" placeholder="Message" />
      </div>
    </div>
    <div class="col-dx">
      <h4>Example Inc.</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>

      <div class="row">
        <i class="fa-solid fa-phone"></i>
        <span>+1 (305) 1234-5678</span>
      </div>
      <div class="row">
        <i class="fa-solid fa-envelope"></i>
        <span>hello@example.com</span>
      </div>
      <div class="row">
        <i class="fa-solid fa-location-dot"></i>
        <span>Main avenue, 987</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactSection",
};
</script>

<style lang="scss" scoped>
.contact {
  display: flex;
  justify-content: center;
  justify-content: space-evenly;
  padding-top: 4.6875rem;
  padding-bottom: 4.6875rem;

  .col-sx {
    width: 25rem;
  }
  .col-dx {
    margin-top: 1.5625rem;
    width: 18.75rem;

    p {
      padding-top: 0.9375rem;
      padding-bottom: 0.9375rem;
    }
  }
  .row {
    display: flex;
    flex-direction: row;
    vertical-align: middle;
  }
}
.uno,
.due,
.tre {
  display: flex;
  justify-content: space-evenly;
}
input {
  background-color: rgb(202, 202, 202);
  width: 45%;
  padding: 0.9375rem;
  margin: 8px 8px;
  box-sizing: border-box;
  border-radius: 0.25rem;
  border: none;
}
.big {
  width: 94%;
  height: 7.8125rem;
}
svg {
  color: #058283;
  line-height: 0.625rem;
  background-color: #cce3de;
  padding: 0.5rem;
  border-radius: 50%;
  vertical-align: middle;
}
.touch {
  background-color: #cce3de;
  color: #058283;
  padding: 0.1875rem;
}
.top h6 {
  color: #058283;
}
</style>
