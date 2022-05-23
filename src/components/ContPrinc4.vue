<script>
export default {data () {
        return {
            bit_coin: 0,
            real: 0
        }
    },
    methods: {
        converter() {
            this.bit_coin = this.real / 145.619,19
            this.bit_coin = this.bit_coin.toFixed(2)
        }
    }};
</script>

<template>
    <div class="geral">
        <h3>Real para bit-coin</h3>
        <div class="entrada">
            <article class="money4">
                <input placeholder="Valor em Real" type="number" id="valor4" v-model="real">
            </article>

            <article class="convert4">
                <input placeholder="Valor em Bit-coin" type="text" disabled id="moeda4" v-model="bit_coin">
            </article>
        </div>

        <button id="btnCalcular" @click="converter">Converter</button>
    </div>
</template>