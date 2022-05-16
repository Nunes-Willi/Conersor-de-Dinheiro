<script>
export default {};
</script>

<template>
    <div class="geral">
        <div class="entrada">
            <article class="money">
                <input placeholder="Valor em Dólar" type="number" id="valor">
            </article>

            <article class="convert">
                <input placeholder="Valor em Real" type="text" disabled id="moeda">
            </article>
        </div>

        <button id="btnCalcular">Calcular</button>
    </div>
</template>
