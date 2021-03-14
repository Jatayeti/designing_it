<template>
    <div class="vacancy">
        <div class="wrap">
            <div class="go-back">
                <button @click="$router.go(-1)">
                    <img src="../assets/images/small-left-top-arrow.png" alt="">
                    Back
                </button>
            </div>

            <div class="row">
                <div class="vacancy__title">
                    <h1>Senior Full Stack Developer</h1>

                    <p>We are looking for a Senior Full Stack Developer with 5+ years of experience.</p>

                    <p>
                        If you are comfortable around both front-end and back-end coding languages, development frameworks and third-party libraries we would love to talk with you.
                    </p>

                    <p>
                        You will get a chance to work at our digital marketing company - DesigningIT, where our mission is to help international companies grow their business both at home and abroad.
                    </p>
                </div>

                <div class="vacancy__apply">
                    <button
                        type="button"
                        @click="openApplyVacancyModal"
                    >
                        Apply
                    </button>
                </div>
            </div>

            <div class="row">
                <div class="divider"></div>
            </div>

            <div class="row">
                <div class="vacancy__des">
                    <h1>Who we are</h1>
                    <p>
                        DesigningIT is a US based full-service digital agency, that was founded in 2003 and is actively growing locations in Asia, Europe and the United States.
                        <br>
                        Our team focuses on performance marketing on a global scale. We help companies plan, build and grow their digital presence. Our core disciplines include digital marketing strategies. UX/UI solutions, modern front end code, CMS integration, and online marketing in the form of SEO and PPC.
                    </p>
                </div>
            </div>
            
            <div class="row">
                <div class="vacancy__list">
                    <h1>Responsibilities</h1>
                    
                    <ul>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Code websites from Figma, using modern Front end technologies
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Integrate with CMS systems such as CraftCMS (twig), ExpressionEngine, and Wordpress
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Headless CMS integrations, API connections to third party solutions.
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Build highly usable, fast and responsive user interfaces for desktop, tablet, and mobile;
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Collaborate with the design team to implement pixel perfect designs.
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Responsible for development of new highly-responsive, web-based user interface
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Work independently and collaborate with the rest of the development team
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Write clean,robust code backed by automated unit tests with full coverage ·
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Evaluate and recommend software components and practices to help keep the product competitive
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Work with product team and UI/UX designers
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Learn and understand user interactions
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Develop a flexible and well-structured front and back end architecture
                        </li>
                    </ul>
                </div>
            </div>

            <div class="row">
                <div class="vacancy__list">
                    <h1>Required Skills</h1>

                    <ul>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Minimum 4 years experience with HTML5/CSS3;
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Minimum 2 years experience with Javascript (Bootstrap, JQuery).
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Gulp, Webpack or similar;
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Minimum 2 years experience with PHP
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Local Servers (MAMP) or Virtual Machines (Vagrant);
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            A solid understanding of web servers (DNS, A Records, Servers, IP's, Nameservers etc), access
                        </li>
                    </ul>

                    <span>++ A huge plus for TWIG template knowledge</span>
                </div>
            </div>

            <div class="row">
                <div class="vacancy__list">
                    <h1>Desired Skills</h1>

                    <ul>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Experience working with CMS (we use ExpressionEngine, CraftCMS, and Wordpress);
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Experience working with Angular, React, Node, Tailwind, Foundation
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Experience working with Laravel, Yii2, Symfony
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            An understanding of solid SEO practices: Schema, On-Page SEO, Meta-Data;
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Proficiency with Photoshop and Sketch;
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Experience in adaptive/responsive web development;
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            CSS including (SASS or LESS Precompiled Languages);
                        </li>
                    </ul>
                </div>
            </div>

            <div class="row">
                <div class="vacancy__list">
                    <h1>What do we offer</h1>

                    <ul>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Competitive Salary in USD
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Work from home / Remote.
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Full time
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Flexible working hours Monday-Friday
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Annual paid vacation and covered sick leaves, paid overtimes
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            The opportunity for professional growth
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Friendly atmosphere (an awesome team of professionals always ready to help)
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Participation in conferences
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Growth opportunities inside the company
                        </li>
                        <li>
                            <img src="../assets/images/small-list-icon.png" alt="">
                            Established Company 15+ years in the business
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Vacancy",

        methods: {
            openApplyVacancyModal() {
                this.$root.$emit('show-vacancy-modal');
            }
        }
    }
</script>

<style lang="scss">
    .vacancy {
        padding: 3rem 0 12rem 0;

        .wrap {
            position: relative;
            z-index: 1;
            max-width: 1145px;
            width: 100%;
            margin: auto;
        }

        .row {
            width: 100%;
            display: flex;
            justify-content: space-between;

            .divider {
                width: 74%;
                border-top: 1px solid #303030;
                margin: 2rem 0;
            }
        }

        .go-back {
            margin: 0 0 6rem 0;

            button {
                background: none;
                border: none;
                outline: none;
                font-family: 'Montserrat', sans-serif;
                font-weight: bold;
                font-size: 20px;
                line-height: 34px;
                text-transform: uppercase;
                color: #E7B900;
                cursor: pointer;

                &:hover {
                    text-decoration: underline;
                }
            }
        }

        &__title {
            h1 {
                font-family: 'Montserrat', sans-serif;
                font-weight: bold;
                font-size: 46px;
                line-height: 34px;
                color: #fff;
                padding: 0 0 2.1rem 0;
            }

            p {
                font-family: 'Montserrat', sans-serif;
                font-weight: normal;
                font-size: 20px;
                line-height: 30px;
                color: #fff;
                padding: 0 0 .6rem 0;
                width: 87%;
            }
        }

        &__apply {
            padding: 2.2rem .1rem 0 0;

            button {
                border: 1px solid #E7B900;
                background: #E7B900;
                border-radius: 100%;
                display: flex;
                align-items: center;
                justify-content: center;
                width: 165px;
                height: 165px;
                font-family: 'Montserrat', sans-serif;
                font-weight: normal;
                font-size: 14px;
                line-height: 34px;
                color: #1A1A1A;
                text-transform: uppercase;
                cursor: pointer;
            }
        }

        &__des {
            padding: .9rem 0 2.2rem 0;

            h1 {
                font-family: 'Montserrat', sans-serif;
                font-weight: bold;
                font-size: 26px;
                line-height: 34px;
                color: #ffffff;
                padding: 0 0 .4rem 0;
            }

            p {
                font-family: 'Montserrat', sans-serif;
                font-weight: normal;
                font-size: 16px;
                line-height: 26px;
                color: #A4A4A4;
                width: 74%;
            }
        }

        &__list {
            margin: 0 0 2.4rem 0;

            h1 {
                font-family: 'Montserrat', sans-serif;
                font-weight: bold;
                font-size: 26px;
                line-height: 34px;
                color: #ffffff;
                padding: 0 0 .4rem 0;
            }

            ul {
                list-style: none;
                padding: 0;
                margin: 0;

                li {
                    font-family: 'Montserrat', sans-serif;
                    font-weight: normal;
                    font-size: 16px;
                    line-height: 26px;
                    color: #A4A4A4;

                    img {
                        margin: 0 1rem 0 0;
                    }
                }
            }

            span {
                display: block;
                font-family: 'Montserrat', sans-serif;
                font-weight: normal;
                font-size: 16px;
                line-height: 26px;
                color: #A4A4A4;
                padding: 1.4rem 0 0 1.9rem;
            }
        }
    }
</style>