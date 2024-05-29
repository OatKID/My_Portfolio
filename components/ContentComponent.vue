<template>
  <div class="topic"><h2>{{ topic }}</h2></div>
        <div class="content">
            <ul>
                <li v-for="item in list">{{ item }}</li>
            </ul>
          </div>
</template>

<script lang="ts" setup>
  defineProps({
    topic: String,
    list: Array<String>
  })
</script>

<style>

</style>