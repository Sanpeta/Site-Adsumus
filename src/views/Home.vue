<template>        
    <v-content grid-list-xs>
        <Slider/>
        <SobreNos/>
        <Servicos/>
    </v-content>
</template>

<script>
import Slider from '../components/Slider'
import SobreNos from '../components/SobreNos'
import Servicos from '../components/Servicos'
export default {
    components: {
        Slider, SobreNos, Servicos
    }
}
</script>