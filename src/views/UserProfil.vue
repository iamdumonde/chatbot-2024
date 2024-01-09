
import AuthenticatedLayoutAdmin from '@/Layouts/AuthenticatedLayoutAdmin.vue';
<template>
    <AuthenticatedLayoutAdmin>
        <div class="max-w-5xl mx-auto p-6">
            <p class="text-2xl font-semibold mb-4">Profil</p>
            <section class="flex justify-center">
                <div class="bg-gray-200 p-6 rounded-md shadow-md w-full">
                    <div class="flex items-center justify-center mb-6">
                        <img src="../assets/logo.png" class="w-40" alt="User Avatar" />
                    </div>
                    <div class="bg-white p-8 rounded-xl">
                        <h1 class="text-2xl font-semibold mb-2">Profil Information</h1>
                        <p class="text-gray-600 mb-4">
                            Mettez à jour les informations de profil et l'adresse e-mail de votre compte
                        </p>
                        <form @submit.prevent="submit" class="space-y-4">
                            <div class="flex items-center space-x-3">
                                <label for="name" class="text-xl w-32 font-medium text-gray-700">
                                    Username :
                                </label>
                                <input id="name" type="text" class="mt-3 py-3 px-4 border border-gray-300 rounded-md w-full"
                                    v-model="form.userName" required autofocus autocomplete="name" />
                            </div>
                            <div class="flex items-center space-x-3">
                                <label for="email" class="text-xl w-32 font-medium text-gray-700">
                                    Email :
                                </label>
                                <input id="email" type="email"
                                    class="mt-3 py-3 px-4 border border-gray-300 rounded-md w-full" v-model="form.email"
                                    required autocomplete="username" />
                            </div>
                            <div class="text-right">
                                <button type="submit"
                                    class="px-4 py-2 bg-indigo-600 text-white rounded-md hover:bg-indigo-700 focus:outline-none focus:ring focus:border-indigo-500">
                                    Sauvegader
                                </button>
                            </div>
                        </form>
                    </div>
                    <div class="bg-white p-8 mt-4 rounded-2xl">
                        <h1 class="text-2xl font-semibold mb-2">Mettre à jour le mot de passe</h1>
                        <p class="text-gray-600 mb-4">
                            Assurez-vous que votre compte utilise un mot de passe long et aléatoire pour rester en sécurité                        </p>
                        <form @submit.prevent="submit" class="space-y-4">
                            <div class="flex items-center space-x-3">
                                <label for="name" class="text-xl w-32 font-medium text-gray-700">
                                    Current Password :
                                </label>
                                <input id="name" type="text" class="mt-3 py-3 px-4 border border-gray-300 rounded-md w-full"
                                    v-model="form.userName" required autofocus autocomplete="name" />
                            </div>
                            <div class="flex items-center space-x-3">
                                <label for="email" class="text-xl w-32 font-medium text-gray-700">
                                    New Password :
                                </label>
                                <input id="email" type="email"
                                    class="mt-3 py-3 px-4 border border-gray-300 rounded-md w-full" v-model="form.email"
                                    required autocomplete="username" />
                            </div>
                            <div class="flex items-center space-x-3">
                                <label for="email" class="text-xl w-32 font-medium text-gray-700">
                                    Confirm Password :
                                </label>
                                <input id="email" type="email"
                                    class="mt-3 py-3 px-4 border border-gray-300 rounded-md w-full" v-model="form.email"
                                    required autocomplete="username" />
                            </div>
                            <div class="text-right">
                                <button type="submit"
                                    class="px-4 py-2 bg-indigo-600 text-white rounded-md hover:bg-indigo-700 focus:outline-none focus:ring focus:border-indigo-500">
                                    Sauvegader
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </section>
        </div>
    </AuthenticatedLayoutAdmin>
</template>

<script setup>
import AuthenticatedLayoutAdmin from '@/Layouts/AuthenticatedLayoutAdmin.vue';

import { ref } from 'vue';

const form = ref({
    userName: '',
    email: '',
});

const submit = () => {

};
</script>