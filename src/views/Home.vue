<template>        
    <v-content grid-list-xs>
        <Slider/>
        <SobreNos/>
    </v-content>
</template>

<script>
import Slider from '../components/Slider'
import SobreNos from '../components/SobreNos'
export default {
    components: {
        Slider,
        SobreNos,
    }
}
</script>