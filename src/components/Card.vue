<template>
  <q-card inline style="width: 500px">
    <q-card-main class="flex row items-center" style="height: 150px">
      <!-- <q-card-media class="col-3">
        <img src={{card.logo}} style="height: 100%">
      </q-card-media> -->
      <q-card-title class="col-8">
       {{card.title}}
        <p class="text-faded">{{card.subtitle}}</p>
      </q-card-title>
      <div>
        <q-checkbox class="col-1" />
      </div>
    </q-card-main>
    <q-card-separator/>
    <q-card-main style="height: 200px">
      <big
        class="text-right"
      >{{card.description}}</big>
    </q-card-main>
  </q-card>
</template>

<style scoped>
</style>

<script>
export default {
  name: 'Card',
  props: ['card']
}
</script>
