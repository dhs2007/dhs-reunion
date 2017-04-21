<template>
  <map
    :center="{lat:10, lng:10}"
    :map-type-id="terrain"
    :zoom="7"
  ></map>
</template>

<script>
  import {load, Map, Marker} from 'vue-google-maps'
</script>

