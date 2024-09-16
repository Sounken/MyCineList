<template>
    <div class="header-menu">
        <div class="header-user-name">
            <h1>Hello ... ! ☺️</h1>
        </div>

        <div class="header-searchbar header-box">
            <font-awesome-icon :icon="['fas', 'magnifying-glass']" />
            <input type="text" placeholder="Chercher un film" />
        </div>

        <div class="dark-mode header-box">
            <font-awesome-icon :icon="['far', 'moon']" />
        </div>

        <div class="user-menu header-box">
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
    margin: 1rem 2rem;
}

.header-menu .header-box {
    background-color: #FFFFFF;
    border-radius: 44px;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
}

.header-menu .header-searchbar {
    width: 18rem;
    height: 4rem;
}

.header-menu .dark-mode {
    width: 4rem;
    height: 4rem;
}

.header-menu .user-menu {
    width: 4rem;
    height: 4rem;
}
</style>