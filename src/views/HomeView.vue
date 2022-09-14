<template>
  <div class="home">
    <Films></Films> 
  </div>
</template>

<script>
// @ is an alias to /src

import Films from '@/components/Films.vue'

export default {
  name: 'HomeView',
  components: {
    Films,
  }
}
</script>
