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
        <g-image src="~/assets/imgs/vol-3.jpg" alt="Gallery Image Four" />
        <g-image src="~/assets/imgs/vol-1.jpg" alt="Gallery Image Two" />
        <g-image src="~/assets/imgs/vol-2.jpg" alt="Gallery Image Three" />
      </div>
      <div class="future__text">
        <h2>Education Changes The Future</h2>
        <p>
          That’s why we’re developing a <br />
          learning platform that empowers <br />
          teachers and students alike.
        </p>
        <p>
          Our quarterly magazine features US and international child labor and
          justice stories.
        </p>
        <g-link class="btn" to="/read">Read Now</g-link>
      </div>
    </section>

    <section class="mvc">
      <div class="mvc__left">
        <h2>At Media Voices We Do Child Rights</h2>
        <div class="mvc__content">
          <p>Award-winning documentaries on child labor and slavery</p>
          <p class="orange">Stolen Childhoods</p>
          <p class="orange">
            Rescuing Emmanuel
          </p>
          <p class="orange">The Same Heart</p>
          <p class="orange">Children of Bal Ashram</p>
          <p>Like What We do? Consider Supporting</p>
          <div>
            <a
              href="https://www.mediavoicesforchildren.org/donate"
              class="btn btn--mr"
              >Donate</a
            >

            <a
              href="https://www.mediavoicesforchildren.org/our-films-1"
              class="btn btn--dark"
              >See Our Films</a
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

    <section class="exhibit">
      <h2>Beneath the Barcode Photo Exhibit</h2>
      <p>
        Gorgeous travelling exhibition features images of child labor and
        rescued children, accompanied by a downloadable action kit. To arrange
        for an exhibit near you, call Media Voices for Children at 508/693-0752
        or email us [mediavoicesforchildren@gmail.com]
      </p>
      <a
        href="https://www.mediavoicesforchildren.org/barcode-resources"
        class="btn"
        >Explore the Exhibit</a
      >
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
