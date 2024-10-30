<script setup lang="ts">
import { shallowRef } from 'vue'
import type { YMap } from '@yandex/ymaps3-types'
import { YandexMap, YandexMapDefaultSchemeLayer } from 'vue-yandex-maps'

//Можно использовать для различных преобразований
const map = shallowRef<null | YMap>(null)
</script>

<template>
  <h1>Кликните по карте, чтобы узнать адрес</h1>
  <div id="YMapsID" style="width: 600px; height: 400px"></div>
</template>
