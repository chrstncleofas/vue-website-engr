<template>

    <section id="showcase">

        <div class="showcase-content">

            <h1 class="l-heading">

             <span class="we-color">We </span>

             <span class="build-color">Build </span>

             <span class="and-color">and </span>

             <span class="design-color">Design</span>

            </h1>

            <p class="lead-p">
              LEADING INDUSTRY OF PROFESSIONAL ENGINEERS
            </p>

          </div>

    </section>
    
</template>

<script>
export default {
    name: "Showcase"
}
</script>

<style scoped>
    /* Showcase Area ung Malaki image sa baba */
    #showcase {
        background: #333333 url('./img/construction-zoom-background-6.jpg') no-repeat center bottom/cover;
        height: 85vh;
        color: #fff;
    }

    #showcase .showcase-content .l-heading {
        font-size: 60px;
        z-index: 2;
    }

    #showcase .showcase-content .lead-p{
        margin-top: 0;
        font-size: 25px;
        color: var(--secondary-color);
        z-index: 2;
    }

    #showcase .showcase-content {
        display: flex;
        flex-direction: column;
        text-align: center;
        justify-content: center;
        align-items: center;
        height: 100%;
        padding: 0 2rem;

        /* Overlay */
        /* Para medyo Transparent ung Image */
        position: relative;
        top: 65;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.5);
    }
</style>