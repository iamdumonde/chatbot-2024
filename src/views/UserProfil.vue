
import AuthenticatedLayoutAdmin from '@/Layouts/AuthenticatedLayoutAdmin.vue';
<template>
    <AuthenticatedLayoutAdmin>
        <div>
            <p>Profil</p>
            <section>
                <div>
                    <p>Avatar</p>
                    <img src="" alt=""/>
                </div>
                <div>
                    <h1>Profil Information</h1>
                    <p>Mettez à jour les informations de profil et l'adresse e-mail de votre compte</p>
                    <form action="">
                        <div>
                            <label>Username :</label>
                            <input/>
                        </div>
                        <div>
                            <label>Username :</label>
                            <input/>
                        </div>
                        <button type="submit">Sauvegader</button>
                    </form>
                </div>

                <div>

                </div>
            </section>
        </div>
    </AuthenticatedLayoutAdmin>
</template>

<script setup>
    import AuthenticatedLayoutAdmin from '@/Layouts/AuthenticatedLayoutAdmin.vue';
</script>