<template>
    <section class="main-bar">
        <div class="top-bar mt-8">
            <div class="top-left">
                <span class="top-left-text"># Relationship</span> <span class="light-text ml-4">|</span> <i class="fa fa-user ml-4 "></i> <span class="light-text">55</span>
                <p class="top-left-subtext">Lets talk about love and other things maybe.</p>
            </div>
            <div class="top-right">
                <div class="search">
                        <i class="fa fa-search"></i>

                        <input class="search__bar" type="search" placeholder=" Search for friend or chat">
                </div>
            </div>
        </div>
        <p class="date__line"> Today 11:40AM</p>
        <div class="chat__area mt-8">
                <div v-for="i in 2" :key="i" class="left_chat_user flex align-items-center mb-24">

                    <div class="profile">
                        <img
                                class="user__avatar"
                                src="../assets/avatars/Avatar@2x.png"
                                alt="User_Avatar"
                        />

                    </div>
                    <div class="user_chat_details">
                        <span class="ml-8 user__chat">My name is Anne , I think your playlist slaps alot! My name is Anne , I think your playlist slaps alot! </span>
                        <span class="ml-4 chat__date">Tosin F Aug 8, 2019, 7:01 PM</span>
                        <span class="ml-4 chat__reaction">has joined</span>
                    </div>

                </div>


                <div v-for="i in 5" :key="i" class="right_chat_user  mb-24">

                    <div class="user_chat_details">
                        <span class="ml-8 user__chat">This is a very nice Chat Application</span>
                        <span class="ml-4 chat__date">Tosin F Aug 8, 2019, 7:01 PM</span>

                    </div>
                    <img
                            class="user__avatar ml-16"
                            src="../assets/avatars/Avatar@2x.png"
                            alt="User_Avatar"
                    />

                </div>





        </div>

        <div class="search mt-32">

            <input class="search__bar" type="search" placeholder=" Search for friend or chat">

            <div class="icon">
                <i class="ml-24 fa fa-pencil"></i>
                <i class="ml-24 fa fa-picture-o"></i>
                <i class="ml-24 fa fa-user"></i>
            </div>
<!--            <i class=" ml-24 fa fa-user🙂️">🙂️</i>-->
        </div>
    </section>
</template>
<script>
    export default {
        data(){
            return{

            }
        }
    }
</script>
<style lang="sass" scoped>
    @import "../assets/components/MainBar"
</style>