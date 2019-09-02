<template>        
    <v-content grid-list-xs>
        <Slider/>
        <SobreNos/>
        <Servicos/>
        <NossoTime/>
    </v-content>
</template>

<script>
import Slider from '../components/Slider'
import SobreNos from '../components/SobreNos'
import Servicos from '../components/Servicos'
import NossoTime from '../components/NossoTime'

export default {
    components: {
        Slider, SobreNos, Servicos, NossoTime
    }
}
</script>