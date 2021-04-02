<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
import { VueElementTableSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  components: {
   VueElementTableSample,
  }
});
</script>

<template>
  <div id="app">
    <vue-element-table-sample />
  </div>
</template>
