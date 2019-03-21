<template>
  <q-page class="flex column q-ma-lg">
    <h3>Featured</h3>
      <q-page class="flex row justify-between items-start">
        <q-card inline style="width: 500px">
          <q-card-main class="flex row items-center" style="height: 150px">
            <q-card-media class="col-3">
              <img src="../../logoKira.jpg" style="height: 100%">
            </q-card-media>
            <q-card-title class="col-8">Kira
              <p class="text-faded">It's How You Know What's in Your Contract</p>
            </q-card-title>
            <div>
              <q-checkbox class="col-1" v-model="check1"/>
            </div>
          </q-card-main>
          <q-card-separator/>
          <q-card-main style="height: 200px">
            <big class="text-right">Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</big>
          </q-card-main>
        </q-card>

        <q-card inline style="width: 500px">
          <q-card-main class="flex row items-center" style="height: 150px">
            <q-card-media class="col-3">
              <img src="../../logoDoxly.png" style="height: 100%">
          </q-card-media>
          <q-card-title class="col-8">Doxly
            <p class="text-faded">Secure Portal for End to End Transactions</p>
          </q-card-title>
          <div>
            <q-checkbox class="col-1" v-model="check2"/>
          </div>
          </q-card-main>
          <q-card-separator/>
          <q-card-main style="height: 200px">
            <big class="text-right">Doxly’s secure transaction management platform brings control, peace of mind, and velocity to legal transactions.</big>
          </q-card-main>
          </q-card>

          <q-card inline style="width: 500px">
            <q-card-main class="flex row items-center" style="height: 150px">
              <q-card-media class="col-3">
                <img src="../../logoClause.png" style="height: 100%">
              </q-card-media>
              <q-card-title class="col-8">Clause
                <p class="text-faded">Connected Contracting</p>
              </q-card-title>
              <div>
                <q-checkbox class="col-1" v-model="check3"/>
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

<script>
export default {
  data () {
    return {
      check1: false,
      check2: false,
      check3: false
    }
  }
}
</script>
