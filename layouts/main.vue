<template>
<div class="layout-main">
    <Navbar></Navbar>
    <slot/>
</div>
</template>
<style lang="scss">

.layout-main {
    width: 100%;
    min-height: 100vh;
    background: linear-gradient(125deg, #f1f1f1d5,  #e9e9f0de, rgb(255, 255, 255) ),  url(/images/bg.jpg);       
    background-repeat: no-repeat;
    background-size: cover;
}
</style>