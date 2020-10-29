<template>
  <section class="posters">
    <h1>The Stolen Childhoods Collection</h1>
    <p>
      These award- winning documentaries examine the causes of child slavery,
      child labor and the impacts of extreme poverty on children around the
      world. Available on Vimeo for single screening or licensed to your school
      or organization. Click on the thumbnail to learn more and view the trailer
      for each title.
    </p>
    <div class="posters__grid">
      <div class="poster" v-for="poster in posters" :key="poster.title">
        <g-image :src="require(`!!assets-loader!@images/${poster.img}`)" />
        <div class="poster__back">
          <h3>{{ poster.title }} ({{ poster.date }})</h3>
          <p>{{ poster.description }}</p>
          <a :href="poster.link" class="btn">Learn More</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      posters: [
        {
          title: 'Stolen Childhoods',
          date: '2004',
          description: `Narrated by Meryl Streep. The first global documentary on child
            labor examines the lives of a quarter of a billion children whose
            backbreaking labor fuels the global economy and robs them of their
            futures. "Harrowing but hopeful" Dana Stevens, New York
            Times`,
          img: 'stolen-childhoods-poster.jpg',
          link: 'https://vimeo.com/ondemand/stolenchildhoods/145866190',
        },
        {
          title: 'Rescuing Emmanuel',
          date: '2009',
          description: `The story of a thirteen year- old Kenyan boy is a window into the
            desperate lives of a 100 million children, ignored by government and
            all who choose not to see them. "A call to the world that
            cannot be ignored" Reid Maki, Director of Advocacy, Child Labor
            Coalition`,
          img: 'rescuing-emmanuel-poster.jpg',
          link: 'https://vimeo.com/ondemand/rescuingemmanuel/146251072',
        },
        {
          title: 'The Same Heart',
          date: '2015',
          description: `At a time when one billion children live in poverty, The Same Heart
            argues the moral imperative of acting now to raise funds for food,
            medicine, education and climate mitigation. Nine Nobel Laureates
            make the case for swift and decisive action to save children's
            lives.`,
          img: 'same-heart-poster.jpg',
          link: 'https://vimeo.com/146433381',
        },
        {
          title: 'Children of Bal Ashram',
          date: '2018',
          description: `What happens after the raid when terrified child slaves are rescued
            from criminal employers? At Bal Ashram, Nobel Prize winner Kailash
            Satyarthi and his wife Sumedha provide a home, family and a second
            chance at childhood.`,
          img: 'bal-ashram-poster.png',
          link: 'https://vimeo.com/306217853',
        },
      ],
    };
  },
  methods: {
    imgStr(img) {
      return './assets/static/src/assets/imgs/' + img;
    },
  },
};
</script>
