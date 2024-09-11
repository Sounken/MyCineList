<template>
    <div class="menu-container">
        <img src="../../assets/img/logo_MVT.png" alt="logo"/>
        <div class="menu">
            <div class="sub-menu">
                <h2>MENU</h2>

                <ul>
                    <li><font-awesome-icon class="icones" :icon="['fas', 'house']" /> Accueil</li>
                    <li><font-awesome-icon class="icones" :icon="['fas', 'gear']" /> Réglages</li>
                    <li><font-awesome-icon class="icones" :icon="['fas', 'ellipsis-vertical']" /> Autres</li>
                </ul>
            </div>
            <div class="sub-menu">
                <h2>ACTIVITÉ</h2>

                <ul>
                    <li><font-awesome-icon class="icones" :icon="['fas', 'eye']" /> Regardé</li>
                    <li><font-awesome-icon class="icones" :icon="['fas', 'thumbs-up']" /> Aimé</li>
                </ul>
            </div>
        </div>
        <hr>
        <div class="menu-footer">
            <i><font-awesome-icon class="icones" :icon="['fas', 'right-from-bracket']" /> Déconnexion</i>
        </div>
    </div>
</template>


<style>
.menu-container {
    width: 24%;
    height: 94%;
    display: flex;
    position: sticky;
    flex-direction: column;
    align-items: center;
    background-color: #FFFFFF;
    color: #1E1E1E;
    border-radius: 44px;
    margin: 1rem 2rem;
}

.menu-container .sub-menu {
    margin-top: 4rem;
}

.menu-container .menu {
    margin-left: -6rem;
    flex: 1;
}

.menu-container img {
    width: 15rem;
    margin-top: 3rem;
}

.menu-container h2 {
    font-family: 'Alegreya Sans', sans-serif;
    font-size: 19px;
    font-weight: extra-bold;
}

.menu-container hr {
    width: 20rem;
    border-top: 0.5px solid #d3d3d3;
}

.menu-container ul {
    padding: 0;
}

.menu-container li {
    font-size: 23px;
    color: #B4B4B4;
    list-style-type: none;
    display: flex;
    align-items: center;
    padding: 1rem 0;
}

.menu-container i {
    color: rgba(255, 0, 0, 0.54);
    font-size: 26px;
    font-style: normal;
    margin-left: -2rem;
}

.menu-container .menu-footer {
    margin-top: 1rem;
    margin-bottom: 4rem;
}

.menu-container .icones {
    width: 29px;
    height: 26px;
    padding-right: 1rem;
}
</style>