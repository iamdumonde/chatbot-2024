<template>
  <div>
    <div class="inline-block bg-white rounded-md p-3 ml-1">
      <p>Bonjour, vous recherchez la meilleure offre internet, c'est bien là !</p>
    </div>
    <br>
    <div class="inline-block bg-white rounded-md p-4 m-1">
      <p>Commençons par faire connaissance...</p>
      <p>Qu'est-ce qui vous amène à changer de fournisseur ?</p>

      <div class="flex flex-grow mt-3">
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Un super prix</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Un top réseau</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Un bouquet adapté</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Mon déménagement</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Autres</div>
      </div>
    </div>



    <div class="text-right">
      <div class="bg-blue-500 text-white inline-block m-1 p-1 pl-4 pr-4 rounded-lg">Mon déménagement</div>

    </div>

    <div class="">
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>Quel budget mensuel vous convient ?</p>

        <div class="flex mt-3">
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Moins 25 €</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">De 25 € à 50 €</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Plus de 50 €</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Je ne sais pas</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Autres</div>
        </div>
      </div>
    </div>

    <div class="text-right">
      <div>
        <div class="bg-blue-500 text-white inline-block m-1 p-1 pl-4 pr-4 rounded-lg">Moins 25 €</div>
      </div>
    </div>



    <div class="inline-block bg-white rounded-md p-4 m-1">
      <p>Je vois que vous recherchez la qualité au meilleur prix !</p>
      <p>On continue à faire connaissance ?...</p>
      <p>Vous êtes chez qui actuellement ?</p>
      <div class="flex mt-3">
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Orange/Sosh</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Bouygues</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">SFR/Red by SFR</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Free</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Autres</div>
        <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Aucun fournisseur</div>
      </div>
    </div>

    <div class="text-right">
      <div class="bg-blue-500 text-white inline-block m-1 p-1 pl-4 pr-4 rounded-lg">Free</div>
    </div>

    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>Vous êtes actuellement en <strong>Fibre</strong> ou en <strong>ADSL</strong> ?</p>
        <div class="flex mt-3">
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">ADSL</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Fibre</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Je ne sais pas </div>
        </div>
      </div>
    </div>
    <div class="text-right">
      <div class="bg-blue-500 text-white inline-block m-1 p-1 pl-4 pr-4 rounded-lg">Fibre</div>
    </div>

    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>Et vous êtes toujours engagé(e) ?</p>
        <div class="flex mt-3">
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Oui, moins d'1an</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Oui, plus d'1 an</div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Non </div>
          <div class="bg-blue-500 text-white m-1 p-2 rounded-md">Je ne sais pas </div>
        </div>
      </div>
    </div>
    <div class="text-right">
      <div class="bg-blue-500 text-white inline-block m-1 p-1 pl-4 pr-4 rounded-lg">Oui, moins d'1 an</div>
    </div>

    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>Bonne nouvelle !</p>
        <p>Votre nouvel opérateur prend en charge une partie de vos frais de résiliation.</p>
        <p>Fibre ou ADSL, celà peut dépendre de votre code postal !</p>
        <div class="flex justify-center mt-3 border-2 w-fit ml-10 rounded-lg">
          <div class="mt-3 pl-10 pr-10">
            <p>Code Postal</p>
            <input name="" id="" class="border-2 border-teal-400 w-96 mt-2 pl-2" placeholder="75001">
            <div class="text-right">
              <button class="bg-blue-500 text-white m-1 p-1 rounded-md">Suivant</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="text-right">
      <div class="bg-blue-500 text-white inline-block m-1 p-1 pl-4 pr-4 rounded-lg">Suivant</div>
    </div>

    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>Les paiements par compte Nickel ou PCS ne sont pas toujours acceptés.</p>
        <p>Disposez-vous d'un autre type de paiement ?</p>
        <div class="flex justify-center gap-10 mt-3">
          <Button class="bg-blue-500 text-white m-1 p-1 pl-2 pr-2 rounded-md">Oui</Button>
          <Button class="bg-blue-500 text-white m-1 p-1 pl-2 pr-2 rounded-md">Non</Button>
        </div>
      </div>
    </div>
    <div class="text-right">
      <div class="bg-blue-500 text-white inline-block m-1 p-1 pl-4 pr-4 rounded-lg">Oui</div>
    </div>

    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>Merci pour toutes ces informations.</p>
        <p>Je recherche pour vous la meilleure offre.</p>
      </div>
    </div>
    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p><strong>Dernier virage !</strong></p>
        <p>Renseignez vos coordonnées et découvrez votre offre !</p>

        <form action="" method="post">
          <div class="text-right mt-4">
            <div>
              <label for="">Prénom :</label>
              <input class="ml-5 mt-2 border-2 w-72" type="text" name="" id="">
            </div>
            <div>
              <label for="">Nom :</label>
              <input class="ml-5 mt-2 border-2 w-72" type="text" name="" id="">
            </div>
            <div>
              <label for="">Email :</label>
              <input class="ml-5 mt-2 border-2 w-72" type="email" name="" id="">
            </div>
            <div>
              <label for="">Téléphone :</label>
              <input class="ml-5 mt-2 border-2 w-72" type="tel" name="" id="">
            </div>
          </div>
          <div class="text-center flex mt-4">
            <input type="checkbox" name="" id="">
            <p>(case à cocher) En cliquant sur <strong>Je découvre mon offre</strong> vous donnez votre accord <br> pour
              être contacté(e) par e-mail, téléphone, whatsapp au sujet de votre offre, <br> conformément aux conditions
              générale CGU</p>
          </div>
          <div class="text-right">
            <button class="bg-blue-500 text-white m-1 p-1 pl-4 pr-4 rounded-lg">Je découvre mon offre</button>
          </div>
        </form>
      </div>
    </div>
    <div class="text-right">
      <button class="bg-blue-500 text-white m-1 p-1 pl-4 pr-4 rounded-lg">Je découvre mon offre</button>
    </div>

    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>D'après les réponses apportées, l'offre la plus adaptée est chez :</p>
        <p>
          <img src="" alt="">
          <ul class="pl-16 text-blue-800">
            <li> <span class="text-4xl">.</span> La meilleure offre internet du moment !</li>
            <li> <span class="text-4xl">.</span> Le meilleur wifi depuis 3 ans</li>
            <li> <span class="text-4xl">.</span> Et du meilleur rapport uqalité/prix du marché.</li>
          </ul>
        </p>
        <p class="mt-2">Je transmets vos réponses à notre conseiller <strong>Bouygues telecom</strong>, il vous appel d'ici quelques minutes.</p>
        <p>Soyez prêt(e) à décrocher pour profiter de votre offre au plus vite</p>
        <p class="mt-2">Et quant à moi, je vous souhaite une excellente fin de journée et, bien sûr une nouvelle expérience <strong>internet </strong>!</p>
        <p>Surtout restez près de votre téléphone vous allez être appelé</p>
      </div>
    </div>

    <div>
      <div class="inline-block bg-white rounded-md p-4 m-1">
        <p>Je compte sur vous !</p>

        <p>Et si cet échange vous a plu, partagez-le avec vos amis !</p>
        <div class="flex gap-5">
          <div class="flex bg-blue-500 text-white p-1 rounded-lg"> 
            <img src="" alt="">
            <button>Facebook</button>
          </div>
          <div class="flex bg-blue-500 text-white p-1 rounded-lg"> 
            <img src="" alt="">
            <button>Twitter</button>
          </div>
          <div class="flex bg-blue-500 text-white p-1 rounded-lg"> 
            <img src="" alt="">
            <button>WhatsApp</button>
          </div>
          
        </div>
      </div>
    </div>

  </div>
</template>



