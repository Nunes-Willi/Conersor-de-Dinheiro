<script>
export default {
    data() {
        return {
            dolar: 0,
            real: 0
        }
    },
    methods: {
        converter() {
            this.dolar = this.real / 5.08
        }
    }
};
</script>

<template>
    <div class="geral">
        <h3>Real para Dóllar</h3>
        <div class="entrada">
            <article class="money">
                <input placeholder="Valor em Real" type="number" id="valor" v-model="real">
            </article>

            <article class="convert">
                <input placeholder="Valor em Dólar" type="text" disabled id="moeda" v-model="dolar">
            </article>
        </div>

        <button id="btnCalcular" @click="converter">Converter</button>
    </div>
</template>
