<template>
  <tiny-grid-column :title="title"></tiny-grid-column>
</template>

<script>
import { GridColumn } from '@opentiny/vue'

export default {
  props: ['title'],
  components: {
    TinyGridColumn: GridColumn
  }
}
</script>
