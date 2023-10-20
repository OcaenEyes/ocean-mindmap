<!--
 * @Author: OCEAN.GZY
 * @Date: 2023-10-20 17:47:51
 * @LastEditors: OCEAN.GZY
 * @LastEditTime: 2023-10-20 17:56:38
 * @FilePath: /ocean-mindmap/mind-map-bak/web/src/pages/Workbenche/Index.vue
 * @Description: 注释信息
-->
<template>
    <div class="workbencheContainer">
        <div class="workbencheContent">
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Workbenche',
    created () {
        document.title = 'ocean-mindmap'
    }
}
</script>

<style lang="less" scoped>
.workbencheContainer {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;

    .workbencheContent {
        flex-grow: 1;
    }
}
</style>