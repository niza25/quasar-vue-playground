<template>
<q-card inline class="q-ma-sm">
      <q-card-media>
        <img :src="card.logo">
      </q-card-media>
      <q-list>
        <q-item>
          <q-item-side>
            <q-item-tile color="primary" icon="local bar" />
          </q-item-side>
          <q-item-main>
            <q-item-tile label>Bar XYZ</q-item-tile>
            <q-item-tile sublabel>Have a drink.</q-item-tile>
          </q-item-main>
        </q-item>
        <q-item>
          <q-item-side>
            <q-item-tile color="red" icon="local gas station" />
          </q-item-side>
          <q-item-main>
            <q-item-tile label>Gas Station</q-item-tile>
            <q-item-tile sublabel>Fill your gas tank.</q-item-tile>
          </q-item-main>
        </q-item>
        <q-item>
          <q-item-side>
            <q-item-tile color="amber" icon="local movies" />
          </q-item-side>
          <q-item-main>
            <q-item-tile label>Cinema XYZ</q-item-tile>
            <q-item-tile sublabel>Watch a movie.</q-item-tile>
          </q-item-main>
        </q-item>
      </q-list>
    </q-card>
  <!-- <q-card inline style="max-width: 530px">
      <q-item>
      <q-item-side>
        <q-item-tile color="primary">
          <img src={{card.logo}}/>
        </q-item-tile>
      </q-item-side>
      <q-item-main>
        <q-item-tile label>{{card.title}}</q-item-tile>
        <q-item-tile sublabel>{{card.subtitle}}</q-item-tile>
      </q-item-main>
    </q-item>
      <q-item>
        <q-checkbox class="col-1" v-on:change="toggleCheckbox"/>
      </q-item>
    <q-card-separator/>
    <q-card-main>
      <h6 class='text-left'>{{card.description}}</h6>
    </q-card-main>
  </q-card> -->
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
