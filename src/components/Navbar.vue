<template>
    <div class="navbar">
        <div class="navbar__wrap">
            <div class="navbar__logo">
                <router-link to="/">
                    <img src="../assets/images/logotype.png" alt="">
                </router-link>
            </div>

            <ul class="navbar__navs">
                <li class="navbar__nav-item">
                    <router-link to="/">
                        About us
                    </router-link>
                </li>
                <li class="navbar__nav-item">
                    <router-link to="/">
                        Works
                    </router-link>
                </li>
                <li class="navbar__nav-item">
                    <router-link to="/">
                        Services
                    </router-link>
                </li>
                <li class="navbar__nav-item">
                    <router-link to="/">
                        Contact
                    </router-link>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style lang="scss">
    .navbar {
        padding: 1.30rem 0 .9rem 0;
        border-bottom: 1px solid #535353;

        &__wrap {
            max-width: 1240px;
            width: 100%;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        &__navs {
            display: flex;
            list-style: none;
        }

        &__nav-item {
            text-transform: uppercase;
            font-family: 'Montserrat', sans-serif;
            font-weight: 400;
            font-size: 13px;
            line-height: 16px;
            margin: 0 0 0 3.5rem;

            a {
                text-decoration: none;
                color: #fff;
                transition: .3s;

                &:hover {
                    color: #E7B900;
                }
            }
        }
    }
</style>