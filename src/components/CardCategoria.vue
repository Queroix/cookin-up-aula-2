<script lang="ts">
import type ICategoria from "@/interfaces/ICategoria";
import type { PropType } from "vue";
export default {
  props: {
    categoria: { type: Object as PropType<ICategoria>, required: true },
  },
};
</script>

<template>
  <article class="categoria">
    <header class="categoria__cabecalho">
      <img
        :src="`/imagens/icones/categorias_ingredientes/${categoria.imagem}`"
        alt=""
        class="categoria__imagem"
      />
      a
    </header>
  </article>
</template>
