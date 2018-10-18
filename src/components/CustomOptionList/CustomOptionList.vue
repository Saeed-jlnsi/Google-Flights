<template>
    <div :class="$style.customOptionList">
        <span :class="$style.listLabel"><slot>labelName</slot></span>
        <span :class="$style.listIcon">
            <img src="https://www.gstatic.com/images/icons/material/system/2x/arrow_drop_down_white_24dp.png" alt="">
        </span>
    </div>
</template>

<style lang="scss" module>
    @import './customoptionlist';
</style>
