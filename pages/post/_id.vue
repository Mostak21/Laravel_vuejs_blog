<template lang="">
    <div>
        {{id}}
    </div>
</template>
<script>
export default {
  layout: "frontend",
  async asyncData({ params, $axios }) {
    const id = params.id;
    return { id };
  },

  data() {
    return {};
  },

  mounted() {}
};
</script>
<style lang="">
    
</style>