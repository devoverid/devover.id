<script>
definePageMeta({
  layout: "main",
})
</script>
<template>
    <section class="hero">
        <div class="container">
            <h1>Empowering IT Gen-Z Community</h1>
            <p class="hero-desc">A community where everyone improve in a fast-paced way.</p>

            <div class="links">
                <a href="https://instagram.com/devover.id" class="button-link"  target="_blank">
                    <img src="/images/icons/instagram.svg" alt="Devover Instagram Account" class="social-links">
                    <span>@devover.id</span>
                </a>
                <a href="https://facebook.com/DevoverID" class="button-link"  target="_blank">
                    <img src="/images/icons/facebook.svg" alt="Devover Facebook Page" class="social-links">
                    <span>Devover ID</span>
                </a>
                <a href="https://discord.gg/UN8xHgVbGs" class="button-link"  target="_blank">
                    <img src="/images/icons/discord.svg" alt="Devover Discord Server Link" class="social-links">
                    <span>Devover - Gen Z IT Community</span>
                </a>
            </div>
        </div>
    </section>
</template>
<style lang="scss">
$text-color:  rgb(0, 0, 0);;

h1 {
    font-size: clamp(2.5rem, 12vw, 5rem);
    font-weight: 400;
    background: linear-gradient(45deg, rgb(22, 17, 17),  rgb(51, 38, 38));
    background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 3rem;
}
.links {
    margin-top: 3rem;
}
.hero {
    padding: 8rem 0;
    .hero-desc {
        color: $text-color;
        font-size: clamp(1.5rem,1vw, 2rem);
        font-weight: 300;
    }
}
.button-link {
    display: flex;
    gap: .5rem;
    align-items: center;
    margin-bottom: 1rem;
    color: $text-color;

    &:hover {
        color: #5170f1;
        fill: #5170f1;
    }
}
.social-links {
    width: 20px;
}

</style>