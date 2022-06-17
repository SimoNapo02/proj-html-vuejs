<template>
  <div class="footer">
    <div class="col-uno">
      <img src="../../assets/img/logo-5.png" alt="Logo di Nex Gen" />
      <p class="lower-title" style="color: #b6c3d0">
        A Functional HTML Template for Corporate & Bussiness
      </p>
      <div class="contact">
        <span> <i class="fa-solid fa-phone"></i></span>
        +1 (305 1234-5678)
      </div>
      <div class="contact">
        <span><i class="fa-solid fa-envelope"></i></span>
        hello@example.com
      </div>
      <div class="contact">
        <span><i class="fa-solid fa-location-dot"></i></span>
        MainAvenue, 987
      </div>
      <div class="mt-4">
        <div class="green-touch">GET IN TOUCH</div>
      </div>
    </div>
    <div class="col-due">
      <h5>About</h5>
      <ul>
        <li v-for="link in linksAbout" :key="link" class="my-2">
          <a :href="link.url"
            ><font-awesome-icon icon="fa-solid fa-angle-right" class="me-2" />{{
              link.text
            }}</a
          >
        </li>
      </ul>
    </div>
    <div class="col-tre">
      <h5>Transport</h5>
      <ul>
        <li v-for="link in linksTransport" :key="link" class="my-2">
          <a :href="link.url"
            ><font-awesome-icon icon="fa-solid fa-angle-right" class="me-2" />{{
              link.text
            }}</a
          >
        </li>
      </ul>
    </div>
    <div class="col-quattro">
      <h5>Support</h5>
      <ul>
        <li v-for="link in linksSupport" :key="link" class="my-2">
          <a :href="link.url"
            ><font-awesome-icon icon="fa-solid fa-angle-right" class="me-2" />{{
              link.text
            }}</a
          >
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterTop",
  data() {
    return {
      linksAbout: [
        {
          text: "The Company",
          url: "#",
        },
        {
          text: "Institutional",
          url: "#",
        },
        {
          text: "Social & Events",
          url: "#",
        },
        {
          text: "Innovation",
          url: "#",
        },
        {
          text: "Environment",
          url: "#",
        },
        {
          text: "Technology",
          url: "#",
        },
      ],
      linksTransport: [
        {
          text: "Industrialized",
          url: "#",
        },
        {
          text: "Chemicals",
          url: "#",
        },
        {
          text: "Packaged Liquid",
          url: "#",
        },
        {
          text: "Construction",
          url: "#",
        },
        {
          text: "Laminated Wood",
          url: "#",
        },
        {
          text: "And others",
          url: "#",
        },
      ],
      linksSupport: [
        {
          text: "Responsability",
          url: "#",
        },
        {
          text: "Terms of Use",
          url: "#",
        },
        {
          text: "About Cookies",
          url: "#",
        },
        {
          text: "Privacy Policy",
          url: "#",
        },
        {
          text: "Accessibility",
          url: "#",
        },
        {
          text: "Information",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.footer {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  padding-top: 4.6875rem;
  background-image: url("../../assets/img/bg-10.jpg");
  height: 37.5rem;
  overflow: hidden;

  max-width: 1516px;

  .contact {
    font-size: 1.1875rem;
    color: #b6c3d0;
    margin: 0.6875rem 0;
    span {
      margin-right: 0.625rem;
    }
  }
  .col-due,
  .col-tre,
  .col-quattro {
    a {
      color: #b6c3d0;
      text-decoration: none;
      font-size: 1.25rem;
    }

    h5 {
      color: white;
      margin-bottom: 2rem;
      font-size: 1.75rem;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
  }
}
.green-touch {
  background-color: var(--button-color);
  padding-left: 0.9375rem;
  padding-right: 0.9375rem;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-bottom: 5px;
  width: 9.375rem;
}
</style>
