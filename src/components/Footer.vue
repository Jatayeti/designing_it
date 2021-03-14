<template>
    <footer class="footer">
        <div class="footer__wrap">
            <div class="footer__brand">
                <img src="../assets/images/logo-dark.png" alt="">
            </div>

            <ul class="footer__navs">
                <li class="footer__navs-item">
                    <a href="">Home</a>
                </li>
                <li class="footer__navs-item">
                    <a href="">About us</a>
                </li>
                <li class="footer__navs-item">
                    <a href="">Works</a>
                </li>
                <li class="footer__navs-item">
                    <a href="">Services</a>
                </li>
                <li class="footer__navs-item">
                    <a href="">Contact us</a>
                </li>
            </ul>

            <ul class="footer__contacts">
                <li class="footer__contacts-item">
                    info@designingit.com
                </li>
                <li class="footer__contacts-item">
                    (843) 709-8780
                </li>
                <li class="footer__contacts-item">
                    @designingit_com
                </li>
                <li class="footer__contacts-item images">
                    <img src="../assets/images/behance-logo.png" alt="">
                    <img src="../assets/images/dribbble-logo.png" alt="">
                    <img src="../assets/images/facebook-logo.png" alt="">
                </li>
            </ul>
        </div>

        <div class="footer__wrap">
            <div class="footer__rights">
                <span>All rights reserved — 2020 © DesigningIT</span>
            </div>

            <div class="footer__terms">
                <span>Terms of use | Privacy Policy</span>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style lang="scss">
    .footer {
        background: #E7B900;
        padding: 5.1rem 0 0 0;

        &__wrap {
            max-width: 1240px;
            width: 100%;
            margin: auto;
            display: flex;
            justify-content: space-between;
        }

        &__brand {
            width: 43rem;
        }

        &__navs {
            list-style: none;
            width: 13.7rem;

            &-item {
                a {
                    white-space: nowrap;
                    text-decoration: none;
                    color: #1A1A1A;
                    font-family: 'Montserrat', sans-serif;
                    font-weight: normal;
                    font-size: 16px;
                    line-height: 34px;
                }
            }
        }

        &__contacts {
            list-style: none;
            padding-right: 4.2rem;

            &-item {
                white-space: nowrap;
                text-decoration: none;
                color: #1A1A1A;
                font-family: 'Montserrat', sans-serif;
                font-weight: normal;
                font-size: 16px;
                line-height: 34px;

                &.images {
                    padding: 2.5rem 0 0 0;

                    img:first-child {
                        margin: 0 2rem 0 0;
                    }

                    img:nth-child(2) {
                        margin: 0 2.2rem 0 0;
                    }
                }
            }
        }

        &__rights {
            padding: 4.8rem 0 2.1rem 0;
        }

        &__terms {
            padding: 4.8rem 2.8rem 2.1rem 0;
        }
    }
</style>