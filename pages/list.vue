<template>
    <div>
        <el-link href="/">首页</el-link>
    </div>
</template>
<script>
    export default {
        layout: 'list',
        head(){
            return {
                title: 'list',
                meta: [{
                    hid: "description",
                    name: "description",
                    content: "this is funny jokes home page"
                }]
            }
        }
    }
</script>