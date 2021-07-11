<demo>
常规使用
</demo>
<template>
  <Tabs v-model:selected="x">
    <Tab title="导航1">内容1</Tab>
    <Tab title="导航2">内容2</Tab>
  </Tabs>
</template>

<script lang="ts">
import {
  Tabs,
  Tab
} from "../lib/index";
import {
  ref
} from 'vue';
import Demo from './Demo.vue';

export default {
  components: {
    Demo,
    Tabs,
    Tab
  },
  setup() {
    const x = ref('导航2');
    return {
      x
    };
  }
};
</script>