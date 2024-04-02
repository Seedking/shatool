<script setup>

</script>

<template>
    <div id="controller" class="join flex justify-center">
        <select id="since" class="select select-bordered join-item w-3/12">
            <option disabled selected>1.14.5</option>
        </select>
        <select id="until" class="select select-bordered join-item w-3/12">
            <option disabled selected>1.41.9</option>
        </select>
        <button id="b_true" class="btn btn-accent join-item">True</button>
        <button id="b_false" class="btn btn-error join-item">False</button>
    </div>
</template>

<style scoped>
#controller {
    margin-top: 2px;
    margin-bottom: 2px;
}
</style>