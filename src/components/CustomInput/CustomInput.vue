<template>
    <div :class="[$style.customInput,className]">
        <!-- <label v-if="label" for="">{{label}}</label> -->
        <!-- <div v-if="validation" :class="$style.validation">!</div> -->
        <div :class="$style.input">
            <!-- <span v-if="icon" :class="$style.icon"> -->
            <span :class="$style.icon">
                <img src="../../assets/image/location-icon.png" alt="">
            </span>
            <input :name="name" :class="invalidClass" type="text" :placeholder="placeHolder" @input="onInput" :value="value" autocomplete="on">
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" module>
    @import './custominput';
</style>


