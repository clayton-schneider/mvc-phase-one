<template>
  <main>
    <Nav mode="alt" />
    <section class="read">
      <h2 class="headline">Read our latest quarterly magazine</h2>
      <iframe 
        allowfullscreen="true" 
        style="border:none;width:100%;height:500px;" 
        src="//e.issuu.com/embed.html?d=mag_volume_four____&hideIssuuLogo=true&showOtherPublicationsAsSuggestions=true&u=mediavoices">
      </iframe>

      <div class="archive">
        <div class="volume">
          <h3>Last Quarter's Magazine</h3>
          <iframe
            allowfullscreen
            allow="fullscreen"
            style="border:none;width:100%;height:500px;"
            src="//e.issuu.com/embed.html?d=volume_three_with_tisbury_changes&u=mediavoices"
          ></iframe>
        </div>
        <div class="volume">
          <h3>Volume Two</h3>
          <iframe
            allowfullscreen
            allow="fullscreen"
            style="border:none;width:100%;height:500px;"
            src="//e.issuu.com/embed.html?d=volume_two_final-_for_print___with_qr_code_fixed_1&u=mediavoices">
          </iframe>;
        </div>
        <div class="volume">
          <h3>Volume One</h3>
          <iframe
            allowfullscreen
            allow="fullscreen"
            style="border:none;width:100%;height:500px;"
            src="//e.issuu.com/embed.html?d=e-mail_mag_for_print_&u=mediavoices"></iframe>
        </div>
      </div>
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
