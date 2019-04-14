<template>
    <div class="col-xs-12 col-sm-6">
        <ul class="list-group">
            <li class="list-group-item" v-for="index in 10">
                <Server :pos="index">index</Server>
            </li>
        </ul>
    </div>
</template>

<script>
    import Server from "./Server";
    export default {
        name: "Servers",
        components: {Server}
    }
</script>

<style scoped>

</style>