<template>
  <q-page class="flex column q-ma-lg">
    <h3>Featured</h3>
    <q-page class="flex row justify-between items-start">
    <q-card inline style="width: 500px">
      <q-card-main class="flex row items-center" style="height: 160px">
      <q-card-media class="col-3">
        <img src="../../logoKira.jpg" style="height: 100%">
      </q-card-media>
      <q-card-title class="col-7">Kira
         <p class="text-faded">It's How You Know What's in Your Contract</p>
      </q-card-title>
      <div>
      <q-checkbox class="col-2" v-model="check1" checked-icon unchecked-icon/>
      </div>
      </q-card-main>
      <q-card-separator/>
      <q-card-main style="height: 200px">
        <big class="text-right">Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</big>
      </q-card-main>
    </q-card>

    <q-card inline style="width: 500px">
      <q-card-main class="flex row items-center" style="height: 160px">
      <q-card-media class="col-3">
        <img src="../../logoDoxly.png" style="height: 100%">
      </q-card-media>
      <q-card-title class="col-7">Doxly
         <p class="text-faded">Secure Portal for End to End Transactions</p>
      </q-card-title>
      <div>
      <q-checkbox class="col-2" v-model="check1"/>
      </div>
      </q-card-main>
      <q-card-separator/>
      <q-card-main style="height: 200px">
        <big class="text-right">Doxly’s secure transaction management platform brings control, peace of mind, and velocity to legal transactions.</big>
      </q-card-main>
    </q-card>

    <q-card inline style="width: 500px">
      <q-card-main class="flex row items-center" style="height: 160px">
      <q-card-media class="col-3">
        <img src="../../logoClause.png" style="height: 100%">
      </q-card-media>
      <q-card-title class="col-7">Clause
         <p class="text-faded">Connected Contracting</p>
      </q-card-title>
      <div>
      <q-checkbox class="col-2" v-model="check1"/>
      </div>
      </q-card-main>
      <q-card-separator/>
      <q-card-main style="height: 200px">
        <big class="text-right">Clause builds the technology infrastructure for 'connected contracts' to increase the value and improve the management of your business agreements.</big>
      </q-card-main>
    </q-card>
</q-page>
  </q-page>
</template>

<style>
</style>

<script>
export default {
  data () {
    return {
      check1: false
    }
  }
}
</script>
