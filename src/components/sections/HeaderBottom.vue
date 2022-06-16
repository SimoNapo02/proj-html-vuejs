<template>
  <div class="nav">
    <ul>
      <li
        v-for="(link, i) in links"
        :key="i"
        :class="{ active: link.isActive }"
      >
        <a href="#">{{ link.txt }}</a>
      </li>
      <div class="green-touch">GET IN TOUCH</div>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HeaderBottom",
  data() {
    return {
      links: [
        {
          txt: "Home",
          isActive: true,
        },
        {
          txt: "Services",
          isActive: false,
        },
        {
          txt: "Skills",
          isActive: false,
        },
        {
          txt: "Partners",
          isActive: false,
        },
        {
          txt: "Blog",
          isActive: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.nav {
  color: var(--primary-text-color);
  margin-left: 62.5rem;
  margin-top: 1.25rem;
  font-size: 18px;
}
ul {
  display: flex;
  gap: 1rem;
  list-style: none;
  a {
    color: inherit;
    text-decoration: none;
  }
}
.green-touch {
  background-color: var(--button-color);
  padding: 0.3125rem;
  margin-bottom: 5px;
}
</style>
