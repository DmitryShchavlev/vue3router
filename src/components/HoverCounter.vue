<template>
<div>
     <h1>{{ title }}</h1>
     <h2 class="hover_counter"
      @mouseover="incrementCount"
      >Hover {{ count }} times
      </h2>
</div>
</template>

<script>

import CounterMixin from './mixins/counter'

export default {
     name:'HoverCounter',
     mixins: [CounterMixin]
}
</script>
<style scoped>

.hover_counter{
    text-align: center;
    margin: 0px 300px 0px 300px;
    background-color:green ;
}

</style>