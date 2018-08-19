<template>
  <div class="index">
    待创建
    <chart/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Chart from '@/components/Chart.vue'

@Component({
  components: {
  Chart
  }
  })
export default class Index extends Vue {}
</script>
