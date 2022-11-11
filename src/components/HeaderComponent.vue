<template>
  <div class="sfondo-nero"></div>
  <div class="main-nav">
    <img src="../assets/img/dc-logo.png" alt="DC logo" />
    <nav>
      <ul>
        <li v-for="(link, index) in links" :key="index">
          <a href="" :class="{ active: link.current }">{{ link.title }}</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      links: [
        {
          title: "character",
          current: false,
        },
        {
          title: "comics",
          current: true,
        },
        {
          title: "movies",
          current: false,
        },
        {
          title: "tv",
          current: false,
        },
        {
          title: "games",
          current: false,
        },
        {
          title: "collectionable",
          current: false,
        },
        {
          title: "videos",
          current: false,
        },
        {
          title: "fans",
          current: false,
        },
        {
          title: "news",
          current: false,
        },
        {
          title: "shop",
          current: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@use "../assets/partials/variable" as *;
.sfondo-nero {
  background-color: $blacktop;
  width: 100%;
  height: 70px;
}
ul {
  list-style: none;
  display: flex;
  li a {
    list-style: none;
    text-decoration: none;
    text-transform: uppercase;
    margin: 1rem;
    color: black;
    &:hover {
      color: $mainblue;
      border-bottom: 5px solid $mainblue;
      padding-bottom: 70px;
    }
  }
}
.main-nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 2rem 2rem;
}
.active {
  color: $mainblue;
  border-bottom: 5px solid $mainblue;
  padding-bottom: 70px;
}
</style>
