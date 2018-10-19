<template>
    <div>
        <app-header></app-header>
        <div :class="$style.reservationPanel">
            <div :class="$style.optionLists">
                <app-custom-option-list>Round Trip</app-custom-option-list>
                <app-custom-option-list>Economy</app-custom-option-list>
            </div>
            <div :class="$style.departureReturnInputs">
                <app-custom-input></app-custom-input>
                <app-custom-input></app-custom-input>
            </div>
            <div :class="$style.searchButton">
                <app-button :icon="searchIconLink">SEARCH</app-button>
            </div>
        </div>
    </div>
</template>

<script>
import Header from '../components/Header/Header';
import CustomOptionList from '../components/CustomOptionList/CustomOptionList';
import CustomInput from '../components/CustomInput/CustomInput.vue';
import Button from '../components/Button/Button';


export default {
    name: 'Home',
    data() {
        return {
            searchIconLink: '//ssl.gstatic.com/images/icons/material/system/2x/search_white_24dp.png'
        }    
    },
    components: {
        appHeader : Header,
        appCustomInput : CustomInput,
        appButton : Button,
        appCustomOptionList : CustomOptionList
    }
}
</script>

<style lang="scss" module>
    @import './home';
</style>