<template>
  <q-card inline style="max-width: 530px">
      <q-item>
          <q-item-side>
            <img :src="card.logo">
          </q-item-side>
          <q-item-main>
            <q-item-tile label class="q-headline">{{card.title}}</q-item-tile>
            <q-item-tile sublabel class="text-faded q-title">{{card.subtitle}}</q-item-tile>
          </q-item-main>
          <div class='q-mx-md'>
            <q-checkbox v-model="card.checked" v-on:change="toggleCheckbox"/>
          </div>
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
  font-weight: normal;
  margin-top: 0;
}
img{
  height: 80px;
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
