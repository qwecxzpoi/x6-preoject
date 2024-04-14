<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})

const x6Ref = shallowRef('')
</script>

<template>
  <ALayout class="h-full">
    <ALayoutSider>
      123
    </ALayoutSider>
    <ALayoutContent>
      <div ref="x6Ref" />
    </ALayoutContent>
  </ALayout>
</template>
