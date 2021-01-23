<script>
import Vue from 'vue';
import { VueVirtualTreeSample } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueVirtualTreeSample,
  }
});
</script>

<template>
  <div id="app">
    <vue-virtual-tree-sample />
  </div>
</template>
