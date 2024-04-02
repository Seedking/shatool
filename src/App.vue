<script setup>
    import SHACell from './components/sha_cell.vue'
    import AddControllerGit from './components/add_controller_git.vue'
    import AddControllerSolo from './components/add_controller_Solo.vue'
</script>

<template>
    <div role="tablist" class="tabs tabs-bordered flex justify-center">
        <a role="tab" class="tab tab-active">Home</a>
        <a role="tab" class="tab">Setting</a>
    </div>
    <div class="">
        <div id="headerButtons" class="join flex justify-center w-full">
            <input class="input input-bordered join-item w-8/12" placeholder="Link"/>
            <button class="btn join-item w-2/12">Add</button>
            <button class="btn join-item w-2/12">Clear</button>
        </div>
        <add-controller-solo></add-controller-solo>
        <add-controller-git></add-controller-git>
        <div id="window" class="overflow-auto bg-base-200 rounded-lg">
            <div id="pot" class="p-3">
                <SHACell></SHACell>
            </div>
        </div>
        <div id="footerButtons" class="join flex justify-center">
            <button class="btn join-item w-1/2">Copy TXT</button>
            <button class="btn join-item w-1/2">Copy LUA</button>
        </div>
    </div>
</template>

<style scoped>
#headerButtons {
    margin-top: 2px;
    margin-bottom: 2px;
}

#window {
    height: 300px;
    margin: 8px 0 10px;
    padding: 0;
}

#footerButtons {
    margin-top: 4px;
    margin-bottom: 4px;
}
</style>
