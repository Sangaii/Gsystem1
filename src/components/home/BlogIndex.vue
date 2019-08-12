<template>
    <div>
        <blog-header></blog-header>
        <hr/>
        <div>这是首页</div>
        <hr/>
        <blog-footer></blog-footer>
    </div>
</template>

<script>
import BlogHeader from '@/components/common/BlogHeader.vue'
import BlogFooter from '@/components/common/BlogFooter.vue'
export default {
    name: 'BlogIndex',
    components: {BlogHeader, BlogFooter}
}
</script>
