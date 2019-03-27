<template>
  <q-page class="q-mx-lg">
    <h3>Featured</h3>
    <Cards v-bind:cardsData='cardsData' />
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
  components: {
    Cards
  },
  data () {
    return {
      cardsData: [
        {
          id: 1,
          title: 'Kira',
          subtitle: 'It is How You Know What is in Your Contract',
          description: 'Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.',
          logo: '../../logoKira',
          checked: false
        },
        {
          id: 2,
          title: 'Doxly',
          subtitle: 'Secure Portal for End to End Transactions',
          description: 'Doxly’s secure transaction management platform brings control, peace of mind, and velocity to legal transactions.',
          logo: '../../logoDoxly.png',
          checked: false
        },
        {
          id: 3,
          title: 'Clause',
          subtitle: 'Connected Contracting',
          description: 'Clause builds the technology infrastructure for connected contracts to increase the value and improve the management of your business agreements.',
          logo: '../../logoClause.png',
          checked: false
        }
      ]
    }
  }
}
</script>
