<template>
  <q-card>
    <q-list>
      <q-item>
      <q-item-side>
        <q-item-tile color="primary">
          <!-- <img href="{{card.logo}}"/> -->
        </q-item-tile>
      </q-item-side>
      <q-item-main>
        <q-item-tile label>{{card.title}}</q-item-tile>
        <q-item-tile sublabel>{{card.subtitle}}</q-item-tile>
      </q-item-main>
    </q-item>
      <div>
        <q-checkbox class="col-1" />
      </div>
    <q-card-separator/>
    <q-card-main>
      <big>{{card.description}}</big>
    </q-card-main>
    </q-list>
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
