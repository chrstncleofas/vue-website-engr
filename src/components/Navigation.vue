<template>
    <section id="navigation">

        <nav class="navbar">

            <ul class="nav-list">

                <li class="nav-item"><a href="#">Home</a></li>
                <li class="nav-item"><a href="#">About</a></li>
                <li class="nav-item"><a href="#">Service</a></li>
                <li class="nav-item"><a href="#">Gallery</a></li>
                <li class="nav-item"><a href="#">Testimonials</a></li>
                <li class="nav-item"><a href="#">Contacts</a></li>

            </ul>

            <div class="search">

                <input type="search" placeholder="Search........">

            </div>

        </nav>

    </section>
</template>

<script>
export default {
    name: "Navigation"
}
</script>

<style scoped>
/* Navbar Section */
.navbar {
    display: flex;
    position: sticky;
    margin-top: 20px;
    background: var(--third-color);
    overflow: hidden;
    color: var(--secondary-color);
    justify-content: space-between;
    z-index: 1;
    padding: 1rem;
}

.navbar ul {
    display: flex;
    align-items: center;
    list-style: none;
}

.navbar ul li a {
    text-transform: uppercase;
    color: var(--secondary-color);
    padding: 0.75rem;
    margin: 0 1rem;
}

.navbar ul li a:hover {
    background: var(--primary-color);
    border-radius: 5px;
}

.navbar .search input {
    content: 'f002';
    padding: 10px;
    width: 400px;
    border-radius: 5px;
    margin-right: 20px;
    outline: none;
}
</style>