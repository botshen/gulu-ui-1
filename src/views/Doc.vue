<template>
  <div>
    <topnav/>
    <div class="content">
      <aside>边栏</aside>
      <main>主内容</main>
    </div>
  </div>
</template>

<script lang="ts">
import Topnav from '../components/Topnav';

export default {
  name: 'Doc',
  components: {Topnav}
};
</script>

<style scoped>

</style>