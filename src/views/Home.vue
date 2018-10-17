<template>
    <div>
        <app-header></app-header>
        
    </div>
</template>

<script>
import Header from '../components/Header/Header';

export default {
    name: 'Home',
    data() {
        return {

        }    
    },
    components: {
        appHeader : Header,
    }
}
</script>

<style lang="scss" module>
    @import './home';
</style>