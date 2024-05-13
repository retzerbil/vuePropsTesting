<script setup lang="ts">
import { ref } from 'vue'
import Child from './Child.vue';
import { Person } from '../models/Person';

const person = ref<Person>(new Person("Kalle",12));
</script>

<template>
<h3>Här visas innehållet av parent</h3>
<Child :human="person"/>
</template>

<style scoped></style>
