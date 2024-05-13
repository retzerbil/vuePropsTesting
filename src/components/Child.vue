<script setup lang="ts">
import { Person } from '../models/Person';


interface ChildProps{
    human:Person;
}
const props = defineProps<ChildProps>();
</script>

<template>
<h5>Här visas innehållet av child</h5>
<p>{{ human }}</p>
</template>

<style scoped></style>
