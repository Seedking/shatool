<script setup>
</script>

<template>
    <div class="card w-full h-1/2 bg-base-100 shadow-xl">
        <div id="body" class="card-body gap-1">
            <div class="flex justify-between items-center">
                <h2 id="title" class="card-title gap-1">114514.zip</h2>
                <div class="card-actions justify-end gap-1">
                    <button class="btn btn-square btn-xs">
                        Copy
                    </button>
                    <button class="btn btn-square btn-xs">
                        Rst
                    </button>
                    <button class="btn btn-square btn-xs">
                        Del
                    </button>
                </div>
            </div>

            <p id="hashcode" class="text-base-300">1919810</p>
        </div>
    </div>
</template>

<style scoped>
#body {
    padding: 4px 26px 14px;
}

#title {
    margin-top: 2px;
    margin-bottom: 2px;
    line-height: 20px;
    font-size: 15px;
}

#hashcode {
    line-height: 5px;
}
</style>