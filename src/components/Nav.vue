<template>
  <nav v-if="mode == 'home'" class="nav nav--home">
    <h3 class="nav__logo">Media Voices For Children</h3>

    <div class="nav__links">
      <g-link to="/contact">Contact</g-link>
      <a href="https://www.mediavoicesforchildren.org/donate">Donate</a>
      <g-link to="/stream" class="orange">Watch Our Stream</g-link>
    </div>
  </nav>
</template>

<script>
export default {
  props: ['mode'],
};
</script>
