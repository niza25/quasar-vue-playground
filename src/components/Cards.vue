<template>
  <div class='row justify-between'>
    <Card v-for='card in cardsData' :key=card.id :card='card' />
  </div>
</template>

<script>
import Card from './Card'

export default {
  name: 'Cards',
  props: ['cardsData'],
  components: {
    Card
  },
  data () {
    return {
    }
  }
}
</script>
