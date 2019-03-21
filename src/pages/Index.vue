<template>
  <q-page class="flex column q-ma-lg">
    <h3>Featured</h3>
    <q-page class="flex row justify-between">
    <q-card inline style="width: 500px">
      <q-card-main class="flex row items-center">
      <q-card-media>
        <img src="../../logoKira.jpg" style="width: 60px">
      </q-card-media>
      <q-card-title>Kira
         <span slot="subtitle" class="text-faded">It's How You Know What's in Your Contract</span>
      </q-card-title>
      <div>
      <q-checkbox v-model="checked"/>
      </div>
      </q-card-main>
      <q-card-separator/>
      <q-card-main>
        Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.
      </q-card-main>
    </q-card>

    <q-card inline style="width: 500px">
      <q-card-title>Doxley</q-card-title>
      <q-card-separator/>
      <q-card-main>Kira is a powerful machine learning software that identifies, extracts, and analyzes text in your contracts and other documents.</q-card-main>
    </q-card>

    <q-card inline style="width: 500px">
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
