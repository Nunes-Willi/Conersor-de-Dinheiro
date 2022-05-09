<script>
import ContPrinc from "@/components/ContPrinc.vue"
import ContPrinc2 from "@/components/ContPrinc2.vue";
import ContPrinc3 from "@/components/ContPrinc3.vue";
import ContPrinc4 from "@/components/ContPrinc4.vue";

export default {
    components:{ContPrinc, ContPrinc2, ContPrinc3, ContPrinc4}
};
</script>
<template>
<main id="content">
 <h2></h2>
<ul>
    <ContPrinc />

    <ContPrinc2 />

    <ContPrinc3 />

    <ContPrinc4 />
 </ul>
</main>
</template>