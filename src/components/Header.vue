<template>
        <header id="header">

        <div class="contain">

            <div class="header-logo">

                <img class="logo" src="./img/company.png" alt="">

            </div>

            <div class="items">

                <h6 class="title">
                    <span>
                        <i class="fas fa-phone-square"></i> Call </span>Us
                </h6>

                <p class="title-head">09-27-843-2078</p>

            </div>

            <div class="items">

                <h6 class="title">
                    <span>
                        <i class="fas fa-envelope"></i> E-</span>Mail
                </h6>

                <p class="title-head">mrjlconstructionservices@gmail.com</p>

            </div>

            <div class="last-div">

                <h6 class="title">
                    <span>
                        <i class="fas fa-clock"></i> Working </span>Hours
                </h6>

                <p class="title-head">Monday-Saturday | 8am-5pm</p>

            </div>

        </div>

    </header>

</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>


/* Header Section  */
#header .contain {
    display: grid;
    padding-top: 15px;
    padding-bottom: 15px;
    grid-template-columns: 6fr 1.2fr 2.4fr 2fr;
    margin-right: 20px;
    margin-left: 20px;
    margin-top: 20px;
}

#header .contain .logo {
    width: 180px;
}

#header .title {
    text-transform: uppercase;
    padding: 0;
    margin-top: 20px;
    margin-left: 10px;
    margin-bottom: 3px;
    font-size: 19px;
    color: var(--third-color);
}

#header .items {
    border-right: 1px #444444 solid;
}

#header i {
    font-size: 25px;
    color: var(--primary-color);
}

#header .title-head {
    padding: 0;
    margin: 0;
    font-size: 15px;
    margin-left: 10px;
    color: var(--primary-color)
}
</style>