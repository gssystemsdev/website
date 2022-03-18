<script lang="ts" setup>
import { Vue3Lottie } from "vue3-lottie";
import dataCenterJSON from "~/assets/lottie/23491-robot-process-automation.json";

useMeta({
  title: "Gssystems",
  description: "Servicios y soluciones tecnológicas a medida para su empresa.",
});
</script>
<template>
  <!-- <label>{{ t("language") }}</la
    bel> -->
  <!-- <select v-model="locale">
      <option value="en">en</option>
      <option value="ja">ja</option>
    </select> -->
  <section class="flex flex-wrap justify-center items-center self-center">
    <div class="p-4">
      <img class="w-28 m-auto block" src="/logo.png" alt="" />
      <h1 class="text-teal-900 text-3xl md:text-4xl -mb-8 m-auto">
        Estamos trabajando en algo increible...
      </h1>

      <Vue3Lottie
        class="w-4/5 h-80 m-auto"
        :animationData="dataCenterJSON"
        :loop="true"
      />
    </div>
  </section>
</template>
