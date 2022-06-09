<script>
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { SubtreeLibrarySample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  SubtreeLibrarySample,
  // }
});
</script>

<template>
  <div id="app">
    <subtree-library-sample :initCounter="30" />
  </div>
</template>
