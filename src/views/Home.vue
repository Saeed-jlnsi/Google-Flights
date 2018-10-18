<template>
    <div>
        <app-header></app-header>
        <div :class="$style.reservationPanel">
            <div :class="$style.departureReturnInputs">
                <app-custom-input></app-custom-input>
                <app-custom-input></app-custom-input>
            </div>
            <div :class="$style.searchButton">
                <app-button>SEARCH</app-button>
            </div>
        </div>
    </div>
</template>

<script>
import Header from '../components/Header/Header';
import CustomInput from '../components/CustomInput/CustomInput.vue';
import Button from '../components/Button/Button';

export default {
    name: 'Home',
    data() {
        return {

        }    
    },
    components: {
        appHeader : Header,
        appCustomInput : CustomInput,
        appButton : Button
    }
}
</script>

<style lang="scss" module>
    @import './home';
</style>