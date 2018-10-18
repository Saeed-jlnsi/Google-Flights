<template>
    <div :class="$style.button">
        <div :class="$style.btn">
            <span :class="$style.icon">
            <img 
                class="flt-fab-icon" 
                src="//ssl.gstatic.com/images/icons/material/system/2x/search_white_24dp.png" 
                alt="" height="24" width="24" data-atf="3" jstcache="1799">
            </span>
            <slot>Button</slot>
        </div> 
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" module>
    @import './button';
</style>

