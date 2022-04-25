<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoBlock from "@/components/CabecalhoBlock.vue";
import RodapeBlock from "@/components/RodapeBlock.vue";
import BolcoPrincipal from "./components/BolcoPrincipal.vue";

export default {
  components: { MenuLateral, CabecalhoBlock, RodapeBlock, BolcoPrincipal },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoBlock />
  <RodapeBlock />
  <BolcoPrincipal />
</template>
<style></style>
