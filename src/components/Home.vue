<template>
    <div>
        <h1>Trade of View your Portfolio</h1>
        <strong>You may Save & Load your data</strong>
        <strong>Click on 'End Day' to begin a New Day</strong>
        <hr>
        <p>Your Funds: {{ funds }}</p>
    </div>
</template>

<script>
export default {
    computed: {
        funds() {
            return this.$store.getters.funds;
        }
    }
}
</script>
