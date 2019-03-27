<template>
  <q-card inline style="max-width: 530px">
      <q-item>
      <q-item-side>
        <img :src="card.logo" style="width: 70px">
      </q-item-side>
       <q-item-main class="col">
        <q-item-tile label>{{card.title}}</q-item-tile>
        <q-item-tile sublabel class="text-faded">{{card.subtitle}}</q-item-tile>
      </q-item-main>
      <q-checkbox v-model="card.checked" v-on:change="toggleCheckbox"/>
      </q-item>
       <q-card-separator/>
    <q-card-main>
      <h6 class='text-left'>{{card.description}}</h6>
    </q-card-main>
  </q-card>
</template>

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
