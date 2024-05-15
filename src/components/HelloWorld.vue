<template>
  <tiny-grid>
    <tiny-grid-column title="123">
      <tiny-grid-column title="456"> </tiny-grid-column>
    </tiny-grid-column>
  </tiny-grid>
</template>

<script>
import { Grid } from '@opentiny/vue'
import TinyGridColumn from './grid-column.vue'

export default {
  components: {
    TinyGrid: Grid,
    TinyGridColumn
  }
}
</script>
