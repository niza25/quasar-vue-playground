<template>
  <q-page class="flex flex-center justify-around">
   <!--  <h3 class="q-display-2 text-right">Featured</h3> -->
    <q-card inline style="width: 400px">
      <q-card-media>
        <img src="../../logoKira.jpg" style="width: 100px">
      </q-card-media>
      <q-card-title>Kira
         <span slot="subtitle" class="text-faded">It's How You Know What's in Your Contract</span>
         <q-checkbox slot="right" v-model="checked" checked-icon unchecked-icon/>
      </q-card-title>
      <q-card-separator/>
      <q-card-main>
        Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.
      </q-card-main>
    </q-card>

    <q-card inline style="width: 400px">
      <q-card-title>Kira</q-card-title>
      <q-card-separator/>
      <q-card-main>Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</q-card-main>
    </q-card>

    <q-card inline style="width: 400px">
      <q-card-title>Kira</q-card-title>
      <q-card-separator/>
      <q-card-main>Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</q-card-main>
    </q-card>

  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex'
}
</script>
