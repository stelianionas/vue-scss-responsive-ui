<template>
    <div id="app">
        <div class="hamburger-menu" @click="toggleMenu">
            <div class="bar"></div>
            <div class="bar"></div>
            <div class="bar"></div>
        </div>

        <div class="sidebar" :class="{ active: isMenuOpen }">
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Services</li>
                <li>Contact</li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            isMenuOpen: false
        };
    },
    methods: {
        toggleMenu() {
            this.isMenuOpen = !this.isMenuOpen;
        }
    }
};
</script>

<style scoped>
    .hamburger-menu {
        width: 25px;
        display: flex;
        flex-direction: column;
        gap: 5px;
        cursor: pointer;
        z-index: 99;
    }

    .bar {
        width: 27px;
        height: 3px;
        border-radius: 20px;
        background-color: #000000;
    }

    .sidebar {
        position: fixed;
        top: 0;
        right: -100%;
        width: 100%;
        margin-top: 100px;
        height: 100%;
        background-color: #FFFFFF;
        transition: right 0.25s ease;
    }

    .sidebar.active {
        right: 0;
    }

    ul {
        list-style-type: none;
    }

    li {
        height: 100px;
        display: flex;
        align-items: center;
        justify-content: flex-end;
        color: #000000;
        padding-right: 20px;
        border-bottom: 1px solid #DDDDDD;
        cursor: pointer;
    }

    li:active {
        background-color: #CCCCCC;
    }
</style>