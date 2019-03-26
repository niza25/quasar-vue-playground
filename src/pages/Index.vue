<template>
  <q-page>
    <h3>Featured</h3>
    <Card></Card>
  </q-page>
</template>

<style scoped>
h3{
text-align: left;
}
</style>

<script>
import Card from '../components/Card'

export default {
  components:{
    Card
  },
  data () {
    return {
      cardData:[
        {
          title: 'Kira',
          subtitle: 'It is How You Know What is in Your Contract',
          description: 'Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.',
          logo: '../../logoKira.jpg',
          checked: false
        },
         {
          title: 'Doxly',
          subtitle: 'Secure Portal for End to End Transactions',
          description: 'Doxly’s secure transaction management platform brings control, peace of mind, and velocity to legal transactions.',
          logo: '../../logoDoxly.png',
          checked: false
        },
         {
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
