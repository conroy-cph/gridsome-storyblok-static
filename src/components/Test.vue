<template>
  <div class="column test"
       v-editable="blok">
    {{ blok.body }}
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
