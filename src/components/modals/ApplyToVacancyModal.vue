<template>
    <div v-if="show" class="modal">
        <div class="modal__bg" @click="closeModal"></div>

        <div class="modal__content">
            <div class="apply-vacancy">
                <button class="apply-vacancy__close-btn" @click="closeModal">
                    <img src="../../assets/images/exit-icon.png" alt="">
                </button>

                <form class="form" @click.prevent="submit">
                    <div class="form__group">
                        <label for="first_name">First Name</label>
                        <input id="first_name" type="text" placeholder="Enter">
                    </div>
                    <div class="form__group">
                        <label for="last_name">Last Name</label>
                        <input id="last_name" type="text" placeholder="Enter">
                    </div>
                    <div class="form__group">
                        <label for="phone">Contact Phone</label>
                        <input id="phone" type="text" placeholder="+1">
                    </div>
                    <div class="form__group">
                        <label for="email">Email</label>
                        <input id="email" type="text" placeholder="example@gmail.com">
                    </div>

                    <div class="form__row">
                        <label for="message">Message</label>
                        <textarea
                            id="message"
                            placeholder="Enter"
                        ></textarea>
                    </div>

                    <div class="form__row">
                        <button
                            class="upload__btn"
                            type="button"
                        >
                            <img src="../../assets/images/upload-icon.png" alt="">
                            Upload your CV
                        </button>
                    </div>

                    <div class="form__apply-btn">
                        <button
                            type="submit"
                        >
                            Apply
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "ApplyToVacancyModal",

        data () {
            return {
                show: false
            }
        },

        created() {
            this.$root.$on('show-vacancy-modal', this.showModal);
        },

        beforeDestroy() {
            this.$root.$off('show-vacancy-modal', this.showModal);
        },

        methods: {
            showModal() {
                this.show = true;
            },

            closeModal() {
                this.show = false;
            },

            submit() {
                // this.closeModal();
            }
        }
    }
</script>

<style lang="scss">
    .modal {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        z-index: 100;

        &__bg {
            position: absolute;
            z-index: -1;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,.5);
        }

        .apply-vacancy {
            position: relative;
            z-index: 1;
            border: 0.5px solid #E7B900;
            width: 1140px;
            padding: 5.8rem 6rem 3rem 6rem;
            box-sizing: border-box;
            background: #000;

            &__close-btn {
                position: absolute;
                top: 1.4rem;
                right: .9rem;
                border: none;
                background: transparent;
                outline: none;
                cursor: pointer;
            }

            .form {
                width: 100%;
                display: flex;
                flex-wrap: wrap;

                &__group {
                    width: 28.6rem;
                    margin: 0 1.9rem 2rem 0;

                    &:nth-child(2n) {
                        margin: 0;
                    }

                    label {
                        display: block;
                        font-family: 'Montserrat', sans-serif;
                        font-weight: normal;
                        font-size: 20px;
                        line-height: 30px;
                        color: #fff;
                        margin: 0 0 .6rem 0;
                    }

                    input {
                        border: 1px solid #303030;
                        box-sizing: border-box;
                        background: transparent;
                        font-family: 'Montserrat', sans-serif;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 16px;
                        line-height: 30px;
                        color: #c4c4c4;
                        outline-color: #E7B900;
                        width: 100%;
                        padding: .9rem 1.4rem;
                    }
                }

                &__row {
                    width: 100%;
                    margin: 0 0 1.2rem 0;

                    label {
                        display: block;
                        font-family: 'Montserrat', sans-serif;
                        font-weight: normal;
                        font-size: 20px;
                        line-height: 30px;
                        color: #fff;
                        margin: 0 0 .5rem 0;
                    }

                    textarea {
                        border: 1px solid #303030;
                        box-sizing: border-box;
                        background: transparent;
                        font-family: 'Montserrat', sans-serif;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 16px;
                        line-height: 30px;
                        color: #c4c4c4;
                        outline-color: #E7B900;
                        width: 100%;
                        padding: 1rem 1.4rem 2.5rem 1.4rem;
                        resize: none;
                    }

                    .upload__btn {
                        display: flex;
                        justify-content: center;
                        white-space: nowrap;
                        font-family: 'Montserrat', sans-serif;
                        font-style: normal;
                        font-weight: bold;
                        font-size: 20px;
                        line-height: 34px;
                        color: #E7B900;
                        text-transform: uppercase;
                        outline: none;
                        padding: 0;
                        margin: 0;
                        background: transparent;
                        border: none;
                        cursor: pointer;

                        img {
                            margin: 0 1rem 0 0;
                        }
                    }
                }

                &__apply-btn {
                    width: 100%;
                    display: flex;
                    justify-content: center;
                    padding: .6rem 0 0 0;

                    button {
                        border: 1px solid #E7B900;
                        border-radius: 100%;
                        background: #E7B900;
                        width: 165px;
                        height: 165px;
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        text-transform: uppercase;
                        outline: none;
                        font-family: 'Montserrat', sans-serif;
                        font-style: normal;
                        font-weight: normal;
                        font-size: 14px;
                        line-height: 34px;
                        cursor: pointer;
                    }
                }
            }
        }
    }
</style>