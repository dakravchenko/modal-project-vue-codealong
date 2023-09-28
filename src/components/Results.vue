<template>
  <p >Reaction time: {{ score }} ms</p>
</template>

<script>
export default {
    props: ['score']
}
</script>

<style>
    .rank {
        font-size: 1.4em;
        color: #0faf87;
        font-weight: bold;
    }
</style>