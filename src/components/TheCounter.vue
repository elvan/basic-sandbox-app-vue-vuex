<template>
  <h3>{{ finalCounter }}</h3>
</template>

<script>
import { mapGetters } from 'vuex';

export default {
  computed: {
    ...mapGetters(['finalCounter']),
  },
};
</script>
