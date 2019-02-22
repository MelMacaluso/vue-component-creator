<template>
  <div>
    <div v-for="(prop,i) in this.$props" :key="i">
      {{prop}}
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  props: ["prop1", "prop2"],
  methods: {}
};
</script>
