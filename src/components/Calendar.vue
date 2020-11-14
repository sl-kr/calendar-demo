<template>
  <v-container>
    <v-calendar :events="events"></v-calendar>
  </v-container>
</template>

<script>
let date = new Date("11-15-2020")

export default {
  data() {
    return {
      events : [
        {
          name: 'name',
          start: date,
          end: date,
          color: 'blue',
          timed: false
        }
      ]
    }
  }
}
</script>