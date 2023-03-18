<template>
  <fab
    :position="position"
    :bg-color="bgColor"
    :actions="fabActions"
    @cache="cache"
    @alertMe="alert"
  ></fab>
</template>

<script>
import fab from "vue-fab";
import { VTooltip } from "v-tooltip";

export default {
  components: {
    fab,
    VTooltip,
  },
  data() {
    return {
      bgColor: "#778899",
      position: "top-right",
      fabActions: [
        {
          name: "cache",
          icon: "cached",
        },
        {
          name: "alertMe",
          icon: "add_alert",
        },
      ],
    };
  },
  methods: {
    cache() {
      console.log("Cache Cleared");
    },
    alert() {
      alert("Clicked on alert icon");
    },
  },
};
</script>
