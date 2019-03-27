<template>
  <q-card inline style="max-width: 520px">
    <q-list>
      <q-item>
      <q-item-side>
        <q-item-tile color="primary">
          <img :src="card.logo"/>
        </q-item-tile>
      </q-item-side>
      <q-item-main>
        <q-item-tile label>{{card.title}}</q-item-tile>
        <q-item-tile sublabel>{{card.subtitle}}</q-item-tile>
      </q-item-main>
    </q-item>
      <div>
        <q-checkbox class="col-1" v-on:change="toggleCheckbox"/>
      </div>
    <q-card-separator/>
    <q-card-main>
      <big class='text-left'>{{card.description}}</big>
    </q-card-main>
    </q-list>
  </q-card>
</template>

<style scoped>
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
