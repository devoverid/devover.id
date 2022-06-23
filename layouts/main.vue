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
    background: linear-gradient(125deg, #a7a7a7,  #d0d1d1);
}
</style>