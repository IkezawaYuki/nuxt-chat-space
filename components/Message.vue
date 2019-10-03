<template>
    <div class="contents__post">
    <div class="contents__post__head">
        <div class="user_name">
        user name
        </div>
        <div class="date">
        日付
        </div>
    </div>
        <p v-if="true" class="contents__post__text">
        メッセージコンテント
        </p>
    
    <!-- todo -->
    <!-- <%= image_tag message.image.url, class: "contents__post__image" if message.image.present? %> -->
    
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>