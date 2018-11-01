<template>
  <nav>
    <ul class="main-nav">
      <li>
        <a class="main-nav__link"
          href="">O nas</a>
      </li>
      <li>
        <a class="main-nav__link"
          href="">Wideo</a>
      </li>
      <li>
        <a class="main-nav__link"
          href="">Oferta</a>
      </li>
      <li>
        <a class="main-nav__link"
          href="">Kontakt</a>
      </li>
      <li>
        <a class="main-nav__link"
          href="">Pytania i odpowiedzi</a>
      </li>
    </ul>
  </nav>
</template>

<script>
</script>

<style lang="scss">
nav {
  z-index: 2;
  margin-top: 0;
  // margin-bottom: auto;
}
.main-nav {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  text-transform: uppercase;
}
.main-nav__link {
  color: white;
  padding: 25px;
  display: block;
}
</style>
