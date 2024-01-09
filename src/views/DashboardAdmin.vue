<script setup>
import AuthenticatedLayoutAdmin from "@/Layouts/AuthenticatedLayoutAdmin.vue";
import Dropdown from '@/Components/Dropdown.vue';
</script>

<template>
    <AuthenticatedLayoutAdmin>
    <h1>Les scénarios</h1>
    <div class="text-right">
    <button class="bg-blue-300 text-wh rounded-lg p-1">
        Ajouter un Scénario
    </button>
    </div>
    <div class="mt-12 flex flex-wrap gap-4 max-w-5xl mx-auto justify-center">
        <div
                class=" group rounded-3xl border-solid  w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description  h-40">
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid  w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid  w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid  w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid  w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid  w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
        <div
                class=" group rounded-3xl border-solid w-72 h-36 bg-amber-50 text-gray-800 text-xl font-medium pl-2 pr-3 py-2 shadow-sm">
                <div>
                    <div class="flex justify-between sticky top-0">
                        <div class="h-7 w-30 flex items-center justify-center rounded-xl">
                            <div class="text-center "></div>
                        </div>
        
                        <Dropdown>
                            <template #trigger>
                                <button>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20"
                                        fill="currentColor">
                                        <path
                                            d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
                                    </svg>
                                </button>
                            </template>
                            <template #content>	
                                
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out" >
                                    Voir
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Modifier
                                </button>
        
                                <button class="block w-full px-4 py-1 text-left text-sm leading-5 text-gray-700 hover:bg-gray-100 focus:bg-gray-100 transition duration-150 ease-in-out">
                                    Supprimer
                                </button>
                            </template>
                        </Dropdown>
        
        
                    </div>
                    <div class="description overflow-y-auto h-40">
                        <!-- <h2 class="mt-1 ml-1 font-medium text-gray-00 ">titre</h2> -->
                    <p class="mt-4 text-sm ml-1 leading-relaxed text-center">
                        Nom du Scénario
                    </p>
                    
                    </div>
                </div>
            </div>
    </div>

</AuthenticatedLayoutAdmin></template>
