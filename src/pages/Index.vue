<template>
  <main>
    <Nav mode="home" />

    <section class="landing">
      <div class="landing__container">
        <h1 class="headline headline--larger">
          Fighting For Child Rights <br />
          Through Education
        </h1>
        <p class="paragraph landing__text">
          Welcome to Media Voices for Children&#39;s child rights learning
          platform. Here you can view our documentaries on child labor and
          access the tools and information you need to help millions of children
          at home and around the world have a decent life.
        </p>
        <a
          href="https://www.mediavoicesforchildren.org/donate"
          target="blank"
          class="btn"
          >Donate</a
        >
      </div>
    </section>

    <div class="movie">
      <h2 class="headline">Children of Bal Ashram</h2>
      <p class="paragraph paragraph--smaller mb">
        Our latest documentary is a testament to the hope and resilience of
        children. Meet the Children of Bal Ashram, a family you will never
        forget. From slavery to the front lines of the war to end child labor,
        the Children of Bal Ashram inspire and are out to change the world.
        <br />
        Winner: Special Jury Prize, Tucson International Film Festival
      </p>
      <g-link to="/stream" class="btn">Watch Children of Bal Ashram</g-link>
    </div>

    <section class="mvc">
      <div class="mvc__left">
        <h2 class="headline">At Media Voices We Do Child Rights</h2>
        <div class="mvc__content">
          <p class="paragraph paragraph--larger mb">
            Dig deeper into the causes of child labor and what actions we can
            take personally to end it. Filled with apps, videos, links to
            organizations and successful programs this guide is appropriate for
            grades 8-12 and for anyone interested in becoming an advocate for
            children. Covers child labor world-wide including the U.S.
          </p>

          <div>
            <g-link to="/study-guide" class="btn btn--mr"
              >Acess The Study Guide</g-link
            >
          </div>
        </div>
      </div>
      <div class="mvc__img-container">
        <g-image
          class="mvc__img"
          src="~/assets/imgs/study-guide.jpg"
          alt="About Us Image"
          width="500"
          height="648"
        />
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
        <h2 class="headline">Education Changes The Future</h2>
        <p class="paragraph paragraph--larger">
          Media Voices Quarterly Newsletter brings commentary, art, photography
          and poetry from a broad range of perspectives. Free to read online and
          download.
        </p>
        <p class="paragraph">
            Our latest, Vol. 4, focuses on the environment, Indigenous voices, child labor in cocoa and agriculture.
        </p>
        <g-link class="btn" to="/read">Read Now</g-link>
      </div>
    </section>

    <Posters />

    <section class="exhibit">
      <h2 class="headline">Beneath the Barcode Photo Exhibit</h2>
      <p class="paragraph paragraph--smaller">
        Beneath the Barcode is a photo exhibit aimed at middle and high schools
        and shows through iconic photography how children factor into the
        production, transport, manufacturing, refining and distribution of all
        the things we eat, buy and use. The exhibit can be downloaded for
        exhibition at your school and comes with an interactive action kit.
      </p>
      <a
        href="https://www.mediavoicesforchildren.org/barcode-resources"
        class="btn"
        target="blank"
        >Explore the Exhibit</a
      >
    </section>

    <Footer />
  </main>
</template>

<script>
import Footer from '~/components/Footer';
import Nav from '~/components/Nav';
import Posters from '~/components/Posters';
export default {
  metaInfo: {
    title: 'Media Voices For Children',
  },
  components: {
    Footer,
    Nav,
    Posters,
  },
};
</script>

<style></style>
