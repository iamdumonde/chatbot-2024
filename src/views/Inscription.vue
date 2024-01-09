<template>
    <div class="flex items-center justify-center h-screen bg-gray-100">
        <div class=" w-1/3 bg-white p-8 rounded-md shadow-md">
            <div class="flex justify-center">                
                    <!-- <img src="../assets/logo.png" alt="" class="w-20"/> -->
                    <p> <img src="../assets/logo.png" alt="" class="w-20"/> Inscription</p>
            </div>
            <form @submit.prevent="submit" class="mt-6 mb-7">
                <div>
                    <label for="name" class="block text-xl font-medium text-gray-700">
                        Name
                    </label>
                    <input id="name" type="text" class="mt-3 py-3 p-2 border  border-gray-300 rounded-md block w-full"
                        v-model="form.userName" required autofocus autocomplete="name" />
                </div>
                <div class="mt-4">
                    <label for="email" class="block text-xl font-medium text-gray-700">
                        Email
                    </label>
                    <input id="email" type="email" class="mt-3 py-3 p-2 border  border-gray-300 rounded-md block w-full"
                        v-model="form.email" required autocomplete="username" />
                </div>
                <div class="mt-4">
                    <label for="password" class="block text-xl font-medium text-gray-700">
                        Password
                    </label>
                    <input id="password" type="password" class="mt-3 py-3 p-2 border  border-gray-300 rounded-md block w-full"
                        v-model="form.password" required autocomplete="new-password" />
                </div>
                <div class="mt-4">
                    <label for="password_confirmation" class="block text-xl font-medium text-gray-700">
                        Confirm Password
                    </label>
                    <input id="password_confirmation" type="password"
                        class="mt-3 py-3 p-2 border  border-gray-300 rounded-md block w-full" v-model="form.password_confirmation"
                        required autocomplete="new-password" />
                </div>
                <div class="flex items-center justify-between mt-6">
                    <div class="text-xl text-gray-600 hover:text-gray-900">
                        <router-link :to="{name: 'connexion'}">
                            J'ai un compte
                        </router-link >
                    </div>
                    <button type="submit"
                        class="ml-4 px-4 py-2 bg-indigo-600 text-white rounded-md hover:bg-indigo-700 focus:outline-none focus:ring focus:border-indigo-500">
                        S'enregistrer
                    </button>
                </div>
            </form>
        </div>
    </div>
</template>
<script setup>
import {reactive } from 'vue';

const form = reactive({
    userName: '',
    email: '',
    password: '',
    password_confirmation: '',
});

const submit = () => {

};
</script>