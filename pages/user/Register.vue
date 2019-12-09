<template>
  <div>
    <h2>Register</h2>
    <div>
      <button @click="authenticateGithub">Github</button>
    </div>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'

@Component
export default class Register extends Vue {
  mounted() {}

  authenticateGithub(): null {
    alert('firebaseにアップロードされたら実行できる')
    // this.$auth.loginWith('github')
    return null
  }
}
</script>
