<script>
export default {
    data () {
        return {
            euro: 0,
            real: 0
        }
    },
    methods: {
        converter() {
            this.euro = this.real / 5.28
        }
    }
};
</script>

<template>

<div class="geral">
    <h3>Real para Euro</h3>
<div class="entrada">
<article class ="money2">
    <input placeholder="Valor em Real" type="number" id="valor2" v-model="real">
</article>

<article class="convert2">
    <input placeholder="Valor em Euro" type="text" disabled id="moeda2" v-model="euro">
</article>
</div>

<button id="btnCalcular" @click="converter">Converter</button>
</div>
<div>

</div>

</template>
