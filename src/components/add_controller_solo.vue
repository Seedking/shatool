<script setup>

</script>

<template>
    <div id="controller" class="join flex justify-center">
        <p id="display">114514</p>
        <button class="btn btn-accent join-item w-2/12">True</button>
        <button class="btn btn-error join-item w-2/12">False</button>
    </div>
</template>

<style scoped>
#controller {
    margin-top: 2px;
    margin-bottom: 2px;
}

#display {display: inline-flex;
    cursor: pointer;
    appearance: none;
    height: 3rem/* 48px */;
    min-height: 3rem/* 48px */;
    padding-left: 1rem/* 16px */;
    padding-right: 2.5rem/* 40px */;
    padding-right: 2.5rem/* 40px */;
    font-size: 0.875rem/* 14px */;
    line-height: 1.25rem/* 20px */;
    line-height: 2;
    border-radius: var(--rounded-btn, 0.5rem/* 8px */);
    border-width: 1px;
    border-color: var(--fallback-bc,oklch(var(--bc)/0.2));
}
</style>