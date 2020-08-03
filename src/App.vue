<template>
  <div id="app">
    <Header />
    <Navigation />
    <Showcase />
  </div>
</template>

<script>
import Header from './components/Header';
import Navigation from './components/Navigation';
import Showcase from './components/Showcase';


export default {
  name: 'App',
  components: {
    Header,
    Navigation,
    Showcase
  }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap');

/* Variable Root Scope for any Color etc*/

:root{
    --primary-color: rgb(252, 92, 0);
    --secondary-color: #fff;
    --third-color: navy;
}

/* Global Setup ito */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
}

body {
    line-height: 1.4;
    background-color: #eeeeee;
}

/* Mga Set up for reset bawat Element */
a {
    text-decoration: none;
}

p {
    margin: 0.75rem 0;
}

img {
    width: 100%;
}

h1, h2, h3, h4, h5, h6 {
    margin-bottom: .55rem;
    line-height: 1.3;
}

/* Set Color po ng Showcase Content dito ko nilagay sa global*/

.build-color{
    color: var(--primary-color);
}

.we-color{
    color: var(--secondary-color);
}

.design-color{
    color: var(--primary-color);
}

.and-color{
    color: var(--secondary-color);
}

/* Set ng Bawat Container Element */
.container {
    max-width: 1100px;
    margin: auto;
    padding: 0 2rem;
    overflow: hidden;
}

/* Responsive Design */

@media(max-width: 500px) {
    #header .contain {
        grid-template-columns: 1fr;
    }
    #header .contain .items {
        display: none;
    }
    #header .contain .last-div {
        display: none;
    }
    #header .contain .header-logo {
        text-align: center;
    }
    .navbar {
        flex-direction: column;
        align-items: center;
    }
    .navbar .logo {
        margin-bottom: 0.5rem;
        text-align: center;
    }
    .navbar ul {
        padding: 0.5rem;
    }
}
</style>
