<!-- html -->
<template>
  <Input v-model="myvalue" placeholder="请输入"></Input>
</template>

<!-- js -->
<script setup>
import { Input } from 'wview'
import { ref } from 'vue'
const myvalue = ref('')
</script>
