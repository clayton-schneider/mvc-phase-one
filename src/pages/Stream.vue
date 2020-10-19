<template>
  <main>
    <Nav mode="alt" />

    <section class="stream">
      <iframe
        src="https://player.vimeo.com/video/304839811"
        width="100%"
        height="600"
        frameborder="0"
        allow="autoplay; fullscreen"
        allowfullscreen
      ></iframe>
      <p>Now Streaming: <span class="bold">Children Of Bal Ashram</span></p>
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
                community can get involved
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
          <!-- <input type="text" placeholder="First Name" />
          <input type="text" placeholder="Last Name" />
          <input type="email" placeholder="Email Address" />
          <a href="" class="btn">Send Me The Study Guide!</a> -->
        </div>
        <div
          class="ml-form-embed"
          data-account="2013992:s1b0g2g4q1"
          data-form="2645135:z7r7e5"
        ></div>
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
  mounted() {
    (function(m, a, i, l, e, r) {
      m['MailerLiteObject'] = e;
      function f() {
        var c = { a: arguments, q: [] };
        var r = this.push(c);
        return 'number' != typeof r ? r : f.bind(c.q);
      }
      f.q = f.q || [];
      m[e] = m[e] || f.bind(f.q);
      m[e].q = m[e].q || f.q;
      r = a.createElement(i);
      var _ = a.getElementsByTagName(i)[0];
      r.async = 1;
      r.src = l + '?v' + ~~(new Date().getTime() / 1000000);
      _.parentNode.insertBefore(r, _);
    })(
      window,
      document,
      'script',
      'https://static.mailerlite.com/js/universal.js',
      'ml'
    );

    var ml_account = ml('accounts', '2013992', 's1b0g2g4q1', 'load');
  },
};
</script>
