<template>
    <div class="box is-info">
        <h2>The count is: {{count}}</h2>

        <p>
            <button v-on:click="count += 1">Increment</button>
        </p>
    </div>
</template>

<script>
export default {
    data() {
        return { 
            count: 0
        }
    },
}
</script>

<style >
    .box{
        background: #e3e3e3;
        padding: 10px;
        border: 1px solid #c5c5c5;
        margin-bottom: 5px;
    }
</style>