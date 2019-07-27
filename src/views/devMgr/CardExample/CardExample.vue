<template>
<div class="dev-mgr__card--example">
  <CardSimple title="components/Title/TitleBar.vue 示例" />
</div>
</template>

<script>
import CardSimple from "@pro_common/components/Card/CardSimple.vue"

export default {
  name: "DevMgrCardExample",
  data() {
    return {
      title: "components/Title/TitleBar.vue 示例" // 测试混合git
    }
  },
  components: {
    CardSimple
  }
}
</script>

<style lang="scss" scoped>
.dev-mgr__card--example {
  box-sizing: border-box;
  padding: 20px;
}
</style>
