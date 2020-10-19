<template>
  <nav v-if="mode == 'home'" class="nav nav--home">
    <g-link to="/"><h3 class="nav__logo">Media Voices For Children</h3></g-link>

    <div class="nav__links">
      <g-link class="nav__link nav__link--light" to="/contact">Contact</g-link>
      <a
        class="nav__link nav__link--light"
        href="https://www.mediavoicesforchildren.org/donate"
        >Donate</a
      >
      <g-link to="/stream" class="nav__link nav__link--light orange"
        >Watch Our Stream</g-link
      >
    </div>
  </nav>
  <nav v-else-if="mode == 'alt'" class="nav nav--alt">
    <g-link to="/"
      ><h3 class="nav__logo nav__logo--dark">
        Media Voices For Children
      </h3></g-link
    >

    <div class="nav__links">
      <g-link class="nav__link nav__link--dark" to="/contact">Contact</g-link>
      <a
        class="nav__link nav__link--dark"
        href="https://www.mediavoicesforchildren.org/donate"
        >Donate</a
      >
      <g-link to="/stream" class="nav__link nav__link--dark"
        >Watch Our Stream</g-link
      >
    </div>
  </nav>
</template>

<script>
export default {
  props: ['mode'],
};
</script>
