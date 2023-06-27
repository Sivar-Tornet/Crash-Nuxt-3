<template>
    <div class="Main">
        <Alert />
        <Profile />
        <!-- <img src="@/assets/1.jpg" alt=""> -->
        <img src="/1.jpg" alt="">
    </div>
</template>

<script setup>
const { sayHello } = useUtils();

sayHello()
</script>