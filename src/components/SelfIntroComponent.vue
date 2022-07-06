<template>
    
    <div class="p-4 p-md-5 mb-4 text-white rounded bg-dark">
        <div class="col-md-6 px-0">

            <h1 class="display-4 fst-italic">Hello, I am Salim. Welcome to My Portfolio.</h1>
            <p class="my-3">{{ selfIntroContent }}</p>
            
        </div>
    </div>
    
</template>

<script>
    export default {
        data() {
            return {
                selfIntroContent: '...'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>