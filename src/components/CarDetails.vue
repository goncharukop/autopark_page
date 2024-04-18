<template>
    <div class="wrap">
        <CarDescription />
        <LineDivider />

        <CarCharacteristic />
        <LineDivider />

        <CarAdditionalOption />
        <LineDivider />

        <CarSalon />
        <LineDivider />

        <CarOptics />
        <LineDivider />

        <CarBody />
        <LineDivider />

        <CarParkingAssistance />
        <LineDivider />

        <CarSafety />
        <LineDivider />

        <CarMultimedia />
    </div>
</template>

<style>
.wrap {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: left;
    margin-left: 20px;
}
</style>

<script>
import CarDescription from './Car/CarDescription.vue'
import CarCharacteristic from './Car/CarCharacteristic.vue'
import CarAdditionalOption from './Car/CarAdditionalOption.vue'
import CarSalon from './Car/CarSalon.vue'
import CarOptics from './Car/CarOptics.vue'
import CarBody from './Car/CarBody.vue'
import CarParkingAssistance from './Car/CarParkingAssistance.vue'
import CarSafety from './Car/CarSafety.vue'
import CarMultimedia from './Car/CarMultimedia.vue'
import LineDivider from './LineDivider.vue'

export default {
    name: 'CarDetails',

    components: {
        CarDescription,
        CarCharacteristic,
        CarAdditionalOption,
        CarSalon,
        CarOptics,
        CarBody,
        CarParkingAssistance,
        CarSafety,
        CarMultimedia,
        LineDivider
    },

    data: () => ({
        //
    }),
}
</script>