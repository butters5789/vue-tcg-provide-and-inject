<template>
  <li>
    <h3>{{ topicName }}</h3>

    <p>{{ description }}</p>

    <button @click="setActiveTopic(id)">Learn More</button>
  </li>
</template>

<script>
export default {
  inject: ['setActiveTopic'],
  props: ['id', 'topicName', 'description'],
};
</script>
