<template>
  <div class='row justify-between'>
    <Card v-for='card in cardsData' v-bind:key=card.id v-bind:card='card' />
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
