<template>
    <div class="header-menu">
        <div class="header-user-name">
            <h1>Hello Damien! ☺️</h1>
        </div>

        <div class="header-searchbar">
            <font-awesome-icon :icon="['fas', 'magnifying-glass']" />
            <input type="text" placeholder="Chercher un film" />
        </div>

        <div class="dark-mode">
            <font-awesome-icon :icon="['far', 'moon']" />
        </div>

        <div class="user-menu">
            <font-awesome-icon :icon="['fas', 'user']" />
        </div>
    </div>
</template>


<style>
.header-menu {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    background-color: #FFFFFF;
    border-radius: 44px;
    margin: 1rem 2rem;
}
</style>