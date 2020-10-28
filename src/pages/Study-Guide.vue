<template>
  <main>
    <Nav mode="alt" />
    <section class="study">
      <iframe
        allowfullscreen
        allow="fullscreen"
        style="border:none;width:100%;height:500px;"
        src="https://e.issuu.com/embed.html?d=mvc_s_children_of_bal_ashram_study_guide_2020_1_&u=mediavoices"
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
    title: 'Read our study guide',
  },
  components: {
    Nav,
    Footer,
  },
};
</script>
