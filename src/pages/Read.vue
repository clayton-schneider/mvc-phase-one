<template>
  <main>
    <Nav mode="alt" />
    <section class="read">
      <h2>Read our latest quarterly magazine</h2>
      <iframe
        allowfullscreen
        allow="fullscreen"
        style="border:none;width:100%;height:500px;"
        src="//e.issuu.com/embed.html?d=volume_three_with_tisbury_changes&u=mediavoices"
      ></iframe>
    </section>
    <Footer />
  </main>
</template>

<script>
import Footer from '~/components/Footer';
import Nav from '~/components/Nav';

export default {
  metaInfo: {
    title: 'Read our magazines',
  },
  components: {
    Nav,
    Footer,
  },
};
</script>
