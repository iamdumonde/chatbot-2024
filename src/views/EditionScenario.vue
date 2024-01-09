<template>
    <AuthenticatedLayoutAdmin>
        <h1>Edition de scénarios</h1>
        <!-- <div class="text-right">
            <button class="bg-blue-300 text-wh rounded-lg p-1">Ajouter </button>
        </div> -->

        <div class="flex pt-4">
            <div class="w-1/2">
                <form @submit.prevent="soumettreFormulaireQuestion">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="scénario"> ID Scénario</label>
                    <div class="mb-4 m-4">
                        <label class="block text-gray-700 text-sm font-bold mb-2">Question :</label>
                        <textarea v-model="question" type="text" required id="texte" placeholder="Entrez le texte"
                            class="shadow-md appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"></textarea>
                    </div>
                    <div class="mt-2 ml-4 tailleChang">
                        <button type="submit"
                            class="border-2 border-primary bg-blue-600 hover:bg-white text-white hover:text-primary w-fit h-fit px-1 rounded-md font-semibold flex items-center gap-2 disabled:cursor-not-allowed">
                            Créer une question
                        </button>
                    </div>
                </form>
                <form @submit.prevent="soumettreFormulaireReponse">
                    <div class="mb-4 m-4 tailleChang">
                        <label class="block text-gray-700 text-sm font-bold mb-2">Réponse :</label>
                        <input v-model="reponse" type="text" placeholder="Entrez des réponses"
                            class="shadow-md appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline border-none"
                            required />
                    </div>
                    <div class="mt-2 ml-4 tailleChang">
                        <button type="submit"
                            class="border-2 border-primary bg-blue-600 hover:bg-white text-white hover:text-primary w-fit h-fit px-1 rounded-md font-semibold flex items-center gap-2 disabled:cursor-not-allowed">
                            Réponse +
                        </button>
                    </div>
                </form>
            </div>
            <div>
                <div v-if="questions.length > 0">
                    <div  v-for="(q, index) in questions" :key="index"
                     class=" bg-white rounded-md p-4 m-1">
            
                     <p>{{ q.texte }}</p>
                     
                     <ul class="flex flex-grow mt-3">
                            <li v-for="(r, i) in q.reponses" :key="i"
                            class="bg-blue-500 text-white m-1 p-2 rounded-md"><button>{{ r }}</button></li>
            
                    </ul>
                    </div>
                </div>
                <div v-else>
                    <p>Aucune question disponible pour le moment.</p>
                </div>
            </div>
        </div>


    </AuthenticatedLayoutAdmin>
</template>
  
<script setup>
import AuthenticatedLayoutAdmin from "@/Layouts/AuthenticatedLayoutAdmin.vue";
import { ref } from 'vue';

const question = ref('');
const reponse = ref('');
const questions = ref([]);

const soumettreFormulaireQuestion = () => {
    // Ajouter la question à la liste des questions
    questions.value.push({ texte: question.value, reponses: [] });

    // Réinitialiser le champ de question
    question.value = '';
};

const soumettreFormulaireReponse = () => {
    // Ajouter la réponse à la dernière question de la liste
    if (questions.value.length > 0) {
        questions.value[questions.value.length - 1].reponses.push(reponse.value);
    }

    // Réinitialiser le champ de réponse
    reponse.value = '';
}

</script>
  