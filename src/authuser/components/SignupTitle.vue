<template>
  <div>
    <img :src="cherry">
    <h4>
      {{ $t('SIGNUP.TITLE') }}
    </h4>
  </div>
</template>

<script>
import cherry from '@/authuser/assets/cherry.png'

export default {
  created () {
    this.cherry = cherry
  },
}
</script>
