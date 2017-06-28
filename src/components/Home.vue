<template>
    <div>
        <h1>Trade or view your portfolio</h1>
        <h6>You mas Save & Load your data</h6>
        <h6>Click end day to begin new day</h6>
        <hr>
        <p>Your funds: {{funds}}</p>
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