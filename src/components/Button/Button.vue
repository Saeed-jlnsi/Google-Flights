<template>
    <div :class="$style.button">
        <div :class="$style.btn">
            <span :class="$style.icon">
            <img
                v-if="icon"
                class="flt-fab-icon" 
                :src="link" 
                alt="" height="24" width="24" data-atf="3" jstcache="1799">
            </span>
            <slot></slot>
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

