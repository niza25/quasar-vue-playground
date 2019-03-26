<template>
  <div>
    <div v-for='card in cardsData' v-bind:key=card.id>
      <Card v-bind:card='card' />
    </div>
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
