<script setup>
import Inicio from "./pages/Inicio.vue";
import Historia from "./pages/Historia.vue";
import Geografia from "./pages/Geografia.vue";
import { ref } from "vue";

const pagina = ref(0);
const paginas = [
  { label: "Início", comp: Inicio },
  { label: "História", comp: Historia },
  { label: "Geografia", comp: Geografia },
];
</script>

<template>
  <header>
    <div class="main__menu">
      <a v-for="(aba, idx) in paginas" :key="`aba` + idx" @click="pagina = idx"
        >{{ aba.label }}
      </a>
    </div>
  </header>

  <main>
    <div>
      <KeepAlive>
        <component :is="paginas[pagina].comp" />
      </KeepAlive>
    </div>
  </main>
</template>

<style scoped>
.main__menu {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 50px;
  margin-bottom: 20px;
  border-bottom: 1px solid rgb(78, 78, 78);
}

a {
  padding: 5px 10px;
  font-size: 24px;
  font-weight: 500;
  border-radius: 20px;
  cursor: pointer;
}

@media screen and (max-width: 767px) {
  .main__menu {
    gap: 15px;
  }

  a {
    font-size: 20px;
  }
}
</style>
