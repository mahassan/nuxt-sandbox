<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news</h1>
    </section>
    <section class="featured-posts"> 
      <PostPreview
      id="1"
      thumbnail=""
      title="Hi"
      previewText="Demo"
       />
      <PostPreview
      id="2"
      thumbnail=""
      title="Hello"
      previewText="Demo"
       />
      <PostPreview
      id="3"
      thumbnail=""
      title="sup"
      previewText="Demo"
       />
    </section>
  </div>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>

<style>
</style>
