<template>
  <footer>
    <div class="container">
      <router-link class="logo-font" :to="{ name: 'home', params: {} }">
        BeyondBlog
      </router-link>
      <span class="attribution">
        An interactive Blog from
        <a
          rel="noopener noreferrer"
          target="blank"
          href="https://github.com/darlincode"
          >Dcchuks</a
        >. Code &amp; design licensed under BeyondBlog
      </span>
    </div>
  </footer>
</template>

<script>
export default {
  name: "RwvFooter"
};
</script>
