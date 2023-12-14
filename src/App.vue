<template>
  <div class="ctr">
    <app-questions></app-questions>
    <app-result></app-result>
    <button type="button" class="reset-btn">Reset</button>
  </div>
</template>

<script>
import AppQuestions from "./components/Questions.vue"
import AppResult from "./components/Result.vue"

export default {
  name: 'App',
  components: {
    AppResult,
    AppQuestions,
  }
}
</script>

<style></style>
