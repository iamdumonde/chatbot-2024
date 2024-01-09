<template>
  <div class="flex items-center justify-center h-screen bg-gray-100">
    <div class="w-1/3 bg-white p-8 rounded-md shadow-md">
      <div class="flex justify-center">
        <p>
          <img src="../assets/logo.png" alt="" class="w-20" />
          Inscription
        </p>
      </div>
      <form @submit.prevent="submit" class="mt-6 mb-7">

        <div class="mb-4 relative">
          <label for="name" class="block text-xl font-medium text-gray-700">
            Username
          </label>

          <div class="mt-3 relative">
            <input id="name" type="text" class="py-3 pl-10 pr-3 border border-gray-300 rounded-md block w-full"
              v-model="form.userName" required autofocus autocomplete="name" />

            <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
              <UserIcon class="w-5 h-5 bg-black-100" />
            </div>
          </div>
        </div>

        <div class="mt-4 relative">
          <label for="email" class="block text-xl font-medium text-gray-700">
            Email
          </label>

          <div class="mt-3 relative">
            <input id="email" type="email" class="py-3 pl-10 pr-3 border border-gray-300 rounded-md block w-full"
              v-model="form.email" required autofocus autocomplete="username" />

            <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
              <EnvelopeIcon class="w-5 h-5 bg-black-100" />
            </div>
          </div>
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
            <button @click="handleLoginClick" :disabled="isLoading" class="underline cursor-pointer focus:outline-none">
              {{ isLoading ? 'Chargement...' : 'J\'ai un compte' }}
            </button>
          </div>
          <button type="submit" :disabled="isLoading"
            class="ml-4 px-4 py-2 bg-indigo-600 text-white rounded-md hover:bg-indigo-700 focus:outline-none focus:ring focus:border-indigo-500">
            S'enregistrer
          </button>
        </div>
      </form>
    </div>
  </div>
</template>
  
<script setup>
import { ref } from 'vue';
import { useRouter } from 'vue-router';
import { UserIcon, EnvelopeIcon, LockClosedIcon } from '@heroicons/vue/24/solid'


const isLoading = ref(false);
const router = useRouter();

const form = ref({
  userName: '',
  email: '',
  password: '',
  password_confirmation: '',
});

const submit = () => {
  // Logique de soumission du formulaire
};

const handleLoginClick = async () => {
  try {
    isLoading.value = true;

    // Simulez un chargement pendant 1.5 secondes 
    await new Promise(resolve => setTimeout(resolve, 1500));

    // Redirection vers la page de connexion
    router.push({ name: 'connexion' });
  } finally {
    isLoading.value = false;
  }
};
</script>
  