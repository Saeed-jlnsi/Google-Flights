<template>
    <div :class="$style.customOptionList">
        <span :class="$style.listLabel"><slot>labelName</slot></span>
        <span :class="$style.listIcon">
            <img src="../../assets/image/arrow-dropdown.png" alt="">
        </span>
    </div>
</template>

<style lang="scss" module>
    @import './customoptionlist';
</style>
