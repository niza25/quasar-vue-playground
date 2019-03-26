<template>
  <div class='row justify-around'>
    <Card v-for='card in cardsData' v-bind:key=card.id class='col-4' v-bind:card='card'>
    </Card>
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
