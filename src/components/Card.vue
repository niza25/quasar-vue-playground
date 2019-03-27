<template>
  <q-card inline style="max-width: 530px">
      <q-item>
        <img :src="card.logo">
       <q-item-main>
        <q-item-tile label>{{card.title}}</q-item-tile>
        <q-item-tile sublabel class="text-faded">{{card.subtitle}}</q-item-tile>
      </q-item-main>
      <q-checkbox v-model="card.checked" v-on:change="toggleCheckbox"/>
      </q-item>
       <q-card-separator/>
    <q-card-main>
      <h6>{{card.description}}</h6>
    </q-card-main>
  </q-card>
</template>

<style>
h6{
  text-align: left;
}
img{
  width: 70px;
}
</style>

<script>
export default {
  name: 'Card',
  props: ['card'],
  methods: {
    toggleCheckbox () {
      this.card.checked = !this.card.checked
    }
  }
}
</script>
