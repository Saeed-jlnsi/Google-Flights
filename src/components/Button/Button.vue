<template>
    <div :class="$style.button">
        <div :class="$style.btn">
            <span :class="$style.icon">
            <img
                v-if="icon"
                class="flt-fab-icon" 
                src="../../assets/image/magnifying-glass.svg" 
                alt="" height="20" width="20" data-atf="3" jstcache="1799">
            </span>
            <span><slot></slot></span>
        </div> 
    </div>
</template>

<script>
    export default {
        props : {
            icon:{}
        }
    }
</script>

<style lang="scss" module>
    @import './button';
</style>

