<script>
export default {
  data() {
    return {
        month: null 
    }
  }
}
</script>

<template>
  <label>What month are you looking for? Please enter an integer in the set {1,2,3,...,12}  </label>
  <input id="month" v-model="month">
  <h1 v-if="month == 1">January</h1>
  <h1 v-else-if="month == 2">February</h1>
  <h1 v-else-if="month == 3">March</h1>
  <h1 v-else-if="month == 4">April</h1>
  <h1 v-else-if="month == 5">May</h1>
  <h1 v-else-if="month == 6">June</h1>
  <h1 v-else-if="month == 7">July</h1>
  <h1 v-else-if="month == 8">August</h1>
  <h1 v-else-if="month == 9">September</h1>
  <h1 v-else-if="month == 10">October</h1>
  <h1 v-else-if="month ==11">November</h1>
  <h1 v-else-if="month == 12">December</h1>

</template>
  