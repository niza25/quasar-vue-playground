<template>
  <q-card inline style="width: 500px">
    <q-card-main class="flex row items-center" style="height: 150px">
      <q-card-media class="col-3">
        <img src="../../logoKira.jpg" style="height: 100%">
      </q-card-media>
      <q-card-title class="col-8">
        Kira
        <p class="text-faded">It's How You Know What's in Your Contract</p>
      </q-card-title>
      <div>
        <q-checkbox class="col-1" v-model="check1"/>
      </div>
    </q-card-main>
    <q-card-separator/>
    <q-card-main style="height: 200px">
      <big
        class="text-right"
      >Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</big>
    </q-card-main>
  </q-card>
</template>

<script>
export default {
  name: 'Card',
  data () {
    return {
      check1: false,
      check2: false,
      check3: false
    }
  }
}
</script>