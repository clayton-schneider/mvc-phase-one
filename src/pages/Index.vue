<template>
  <main>
    <Nav mode="home" />
    <section class="landing">
      <div class="landing__container">
        <h1 class="landing__title">
          Fighting For Child Rights <br />
          Through Education
        </h1>
        <p class="landing__text">
          Watch Children of Bal Ashram and download the companion study guide.
        </p>
        <g-link to="/stream" class="btn">Watch The Stream</g-link>
      </div>
    </section>

    <section class="future">
      <div class="gallery">
        <g-image src="~/assets/imgs/gallery-1.jpg" alt="Gallery Image One" />
        <g-image src="~/assets/imgs/gallery-2.jpg" alt="Gallery Image Two" />
        <g-image src="~/assets/imgs/gallery-3.jpg" alt="Gallery Image Three" />
        <g-image src="~/assets/imgs/gallery-4.jpg" alt="Gallery Image Four" />
      </div>

      <div class="future__text">
        <h2>Education Changes The Future</h2>
        <p>
          That’s why we’re developing a <br />
          learning platform that empowers <br />
          teachers and students alike.
        </p>
        <p>
          Want a taste of what is to come? Tune into our streaming of Children
          of Bel Ashram and recieve a free copy of our tagalong study guide
        </p>
        <g-link class="btn" to="/stream">Stream Now</g-link>
      </div>
    </section>

    <section class="mvc">
      <div class="mvc__left">
        <h2>At Media Voices We Do Child Rights</h2>
        <div class="mvc__content">
          <p>Coming over the next months:</p>
          <p><span class="orange">4</span> feature length documentaries</p>
          <p><span class="orange">Quarterly</span> magazine</p>
          <p><span class="orange">1</span> nationwide curriculum</p>
          <p>Like What We do? Consider Supporting</p>
          <div>
            <a
              href="https://www.mediavoicesforchildren.org/"
              class="btn btn--mr"
              >Donate</a
            >
            <a
              href="https://www.mediavoicesforchildren.org/donate"
              class="btn btn--dark"
              >Learn More About Us</a
            >
          </div>
        </div>
      </div>
      <g-image
        src="~/assets/imgs/about-img.jpg"
        alt="About Us Image"
        height="700"
      />
    </section>

    <Footer />
  </main>
</template>

<script>
import Footer from '~/components/Footer';
import Nav from '~/components/Nav';
export default {
  metaInfo: {
    title: 'Media Voices For Children',
  },
  components: {
    Footer,
    Nav,
  },
};
</script>

<style></style>
