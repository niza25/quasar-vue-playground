<template>
  <q-page class="q-mx-lg">
    <h3>Featured</h3>
    <Cards :cardsData='cardsData' />
  </q-page>
</template>

<style scoped>
h3{
text-align: left;
}
</style>

<script>
import Cards from '../components/Cards'

export default {
  name: 'MainPage',
  components: {
    Cards
  },
  data () {
    return {
      cardsData: [
        {
          id: 1,
          title: 'Kira',
          subtitle: 'It\'s How You Know What\'s in Your Contract',
          description: 'Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.',
          logo: 'https://i.ibb.co/FVSvfVn/logoKira.png',
          checked: false
        },
        {
          id: 2,
          title: 'Doxly',
          subtitle: 'Secure Portal for End to End Transactions',
          description: 'Manage the entire legal transaction process from diligence to cosing.',
          logo: 'https://i.ibb.co/qsCxjDw/logo-Doxly.png',
          checked: false
        },
        {
          id: 3,
          title: 'Clause',
          subtitle: 'Connected Contracting',
          description: 'Clause builds the technology infrastructure for connected contracts to increase the value and improve the management of your business agreements.',
          logo: 'https://i.ibb.co/7Y7JL7q/logo-Clause.png',
          checked: false
        }
      ]
    }
  }
}
</script>
