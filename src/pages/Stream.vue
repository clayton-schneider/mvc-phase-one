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
