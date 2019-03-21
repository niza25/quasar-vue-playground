<template>
  <q-page class="flex column q-ma-lg">
    <h3>Featured</h3>
    <q-page class="flex row justify-between">
    <q-card inline style="width: 400px">
      <q-card-main>
      <q-card-media>
        <img src="../../logoKira.jpg" style="width: 100px">
      </q-card-media>
      <q-card-title>Kira
         <span slot="subtitle" class="text-faded">It's How You Know What's in Your Contract</span>
         <q-checkbox slot="right" v-model="checked" checked-icon unchecked-icon/>
      </q-card-title>
      </q-card-main>
      <q-card-separator/>
      <q-card-main>
        Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.
      </q-card-main>
    </q-card>

    <q-card inline style="width: 400px">
      <q-card-title>Doxley</q-card-title>
      <q-card-separator/>
      <q-card-main>Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</q-card-main>
    </q-card>

    <q-card inline style="width: 400px">
      <q-card-title>Clause</q-card-title>
      <q-card-separator/>
      <q-card-main>Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</q-card-main>
    </q-card>
</q-page>
  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex'
}
</script>
