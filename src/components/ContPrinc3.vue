<script>
export default {
    data () {
        return {
            iene: 0,
            real: 0
        }
    },
    methods: {
        converter() {
            this.iene = this.real / 0.039
        }
    }};
</script>

<template>
<div class="geral">
    <h3>Real Iene</h3>
<div class="entrada">
<article class ="money3">
    <input placeholder="Valor em Real" type="number" id="valor3" v-model="real">
</article>

<article class="convert3">
    <input placeholder="Valor em Iene" type="text" disabled id="moeda3" v-model="iene">
</article>
</div>

<button id="btnCalcular" @click="converter">Converter</button>
</div>
</template>