<template>
  <main>
    <Nav mode="alt" />

    <section class="stream">
      <div class="stream__img"></div>
      <p>Now Streaming: <span class="bold">Children Of Bal Ashram</span></p>
      <p>Streaming Until: Sept. 14th 12:00pm</p>
    </section>

    <section class="offer">
      <div class="offer__left">
        <div class="offer__content">
          <h2>Limited Time Offer</h2>
          <p class="offer__exp">
            Get the information and tools you need to advocate for children's
            rights around the world and learn more about the young activists at
            the forefront of today's struggle to end child labor and modern
            slavery.
          </p>
          <div class="offer__benefits">
            <div class="offer__benefit">
              <g-image src="~/assets/imgs/check.svg" alt="benefit" />
              <p>
                Access our seven-part study guide, suitable for remote learning
                for grades 7-12
              </p>
            </div>
            <div class="offer__benefit">
              <g-image src="~/assets/imgs/check.svg" alt="benefit" />
              <p>
                Learn more about youth activism and how you, your students and
                community can make get involved
              </p>
            </div>
            <div class="offer__benefit">
              <g-image src="~/assets/imgs/check.svg" alt="benefit" />
              <p>
                Learn more about Media Voices for Children and receive our
                quarterly magazine on all aspects of child rights
              </p>
            </div>
          </div>
        </div>

        <div class="offer__signup">
          <h3>Complete This Form And We Will Send You Your Study Guide</h3>
          <input type="text" placeholder="First Name" />
          <input type="text" placeholder="Last Name" />
          <input type="email" placeholder="Email Address" />
          <a href="" class="btn">Send Me The Study Guide!</a>
        </div>
      </div>
      <g-image
        src="~/assets/imgs/study-guide.jpg"
        alt="Study Guide"
        height="650"
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
    title: 'Stream Children Of Bal Ashram',
  },
  components: {
    Nav,
    Footer,
  },
};
</script>
