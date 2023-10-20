<!--
 * @Author: OCEAN.GZY
 * @Date: 2023-10-18 19:43:57
 * @LastEditors: OCEAN.GZY
 * @LastEditTime: 2023-10-19 12:34:16
 * @FilePath: /mind-map/web/src/pages/Doc/zh/help3/index.vue
 * @Description: 注释信息
-->
<template>
  <div>
    <h1>打开预览在线文件</h1>
<p>v0.7.0+版本支持打开url中携带的在线文件：</p>
<pre class="hljs"><code>https://wanglin2.github.io/mind-map/#/?fileURL=http://xxx.com/xxx.xmind
</code></pre>
<p>在<code>fileURL</code>参数后带上你的在线文件url即可，目前支持<code>.xmind</code>、<code>.omm</code>、<code>.json</code>、<code>.md</code>后缀的文件url。</p>
<p>需要注意的是你在打开在线文件的情况下编辑并不会修改在线文件，改动会保存在你的浏览器本地，你可以选择导出文件。</p>

  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>