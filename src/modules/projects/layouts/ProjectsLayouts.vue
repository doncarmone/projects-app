<template>
    <div class="flex flex-col">
        <top-menu />
        <main class="flex flex-row">
            <sideMenu />
            <router-view />
        </main>
    </div>
</template>
<script lang="ts" setup>
import TopMenu from '@/modules/common/components/TopMenu.vue'
import SideMenu from '@/modules/projects/components/SideMenu.vue'
</script>
