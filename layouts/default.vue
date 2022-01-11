<template>
    <div>
        <nav>
            <ul class="nav-list">
                <li class="nav-list-item"><nuxt-link to="/">1</nuxt-link></li>
                <li class="nav-list-item"><nuxt-link to="/">2</nuxt-link></li>
                <li class="nav-list-item"><nuxt-link to="/">3</nuxt-link></li>
                <li class="nav-list-item"><nuxt-link to="/">4</nuxt-link></li>
                <li class="nav-list-item"><nuxt-link to="/">5</nuxt-link></li>
            </ul>
        </nav>
        <nuxt />
        <section class="side-bar">
            <div>12</div>
            <div>12</div>
            <div>12</div>
            <div>12</div>
        </section>
    </div>
</template>

<style scoped>
nav{
    width: 100%;
}
.nav-list{
    padding: 0;
    margin: 0;
    list-style-type: none;
    display: flex;
    justify-content: space-evenly;
}
.side-bar{
    float: left;
    width: 150px;
    height: 100px;
}
</style>