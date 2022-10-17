<template>
  <div class="Navbar">
    <div class="logo">Logo</div>
    <div class="menu">
      <ul>
        <li>
          <NuxtLink to="/"><a>Home page</a></NuxtLink>
        </li>
        <li>
          <NuxtLink to="/"><a>Content1</a></NuxtLink>
        </li>
        <li>
          <NuxtLink to="/"><a>Content2</a></NuxtLink>
        </li>
        <li>
          <NuxtLink to="/About"><a>About</a></NuxtLink>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
body {
  margin: 0;
}
.Navbar {
  display: flex;
  justify-content: space-between;
  background-color: aqua;
  align-items: center;
}
.logo {
  color: red;
  margin-left: 2rem;
}
.menu ul {
  display: flex;
}
.menu ul li {
  list-style-type: none;
  margin-left: 2rem;
  margin-right: 1rem;
}
.menu ul li a {
  text-decoration: none;
}
</style>
