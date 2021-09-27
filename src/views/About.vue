<template>
  <div class="about">
    <Tabs v-model="active">
      <Tab title="标签 1">内容 1</Tab>
      <Tab title="标签 2">内容 2</Tab>
      <Tab title="标签 3">内容 3</Tab>
      <Tab title="标签 4">内容 4</Tab>
    </Tabs>
  </div>
</template>

<script>
import { Tab, Tabs } from "vant";

export default {
  components: {
    Tab,
    Tabs,
  },
  data() {
    return {
      active: 2,
    };
  },
};
</script>
