<template>
  <main>
    <Nav mode="alt" />

    <section class="contact">
      <div class="contact__left">
        <h2>Get In Touch</h2>
        <p>
          Questions, streaming requests, other thoughts? <br />We'd love to hear
          from you.
        </p>

        <form name="contact" method="POST" data-netlify="true" action="">
          <input type="text" placeholder="Name" />
          <input type="email" placeholder="Email" />
          <textarea placeholder="Message"></textarea>
          <button type="submit" class="btn">Submit</button>
        </form>
      </div>
      <div class="contact__right"></div>
    </section>
    <Footer />
  </main>
</template>

<script>
import Footer from '~/components/Footer';
import Nav from '~/components/Nav';
export default {
  metaInfo: {
    title: 'Contact Us',
  },
  components: {
    Nav,
    Footer,
  },
};
</script>
