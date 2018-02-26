<template>
    <div id="app">
        <users></users>
    </div>
</template>

<script>

import Test from './components/test'
import Users from './components/users'

export default {
    name: 'app',
    components: {
        Test, Users
    }
}
</script>

<style>
#app {

     text-align: center;


 }
</style>
