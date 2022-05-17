<template>
<div>
     <h1>{{ title }}</h1>
    <button @click="incrementCount">Cliked {{ count }} times</button>
</div>
</template>

<script>

import CounterMixin from './mixins/counter'

export default {
     name:'ClickCounter',
     mixins : [CounterMixin]
}
</script>
<style>
</style>