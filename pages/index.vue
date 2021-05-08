<template>
  <GridWidth>
    <TestComponent />
  </GridWidth>
</template>

<script>
import TestComponent from "~/components/TestComponent";
import GridWidth from "~/components/grid_width/GridWidth";

export default {
  name: 'Startseite',
  components: {TestComponent, GridWidth},
}
</script>
