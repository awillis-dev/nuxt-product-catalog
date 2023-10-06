<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/"> Nuxt Dojo</NuxtLink>
        <ul>
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products">Products</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere, dicta
      quibusdam quis commodi perferendis possimus illo hic, quia delectus
      ducimus placeat, at eaque dolorem mollitia odio nulla soluta odit
      temporibus.
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
