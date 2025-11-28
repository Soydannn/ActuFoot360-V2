<template>
    <footer class="bg-black text-white py-10 px-20">
      <div class="container mx-auto flex justify-between items-start">
  
        <!-- Zone gauche : Logo + texte sous le logo -->
        <div class="flex flex-col items-start">
          <img src="/actufootv2.png" alt="Logo" class="w-16 h-16 mb-3">
          <p class="text-gray-300 max-w-3xs">
            ActuFoot360-V2 – Les dernières actualités du football en temps réel.
          </p>
        </div>
  
        <!-- Zone centrale : Menu rapide -->
        <div class="flex flex-col items-center">
          <h3 class="font-semibold mb-3 text-white">Menu rapide</h3>
          <ul class="space-y-2 text-center">
            <li><router-link to="/" class="hover:text-red-500">Accueil</router-link></li>
            <li><router-link to="/stats" class="hover:text-red-500">Statistiques</router-link></li>
          </ul>
        </div>
  
        <!-- Zone droite : Mentions légales / confidentialité / cookies -->
        <div class="flex flex-col items-end">
          <h3 class="font-semibold mb-3 text-white">Informations</h3>
          <ul class="space-y-2 text-right">
            <li><router-link to="/confidentialite" class="hover:text-red-500">Confidentialité</router-link></li>
            <li><router-link to="/cookies" class="hover:text-red-500">Cookies</router-link></li>
            <li><router-link to="/mentions-legales" class="hover:text-red-500">Mentions légales</router-link></li>
          </ul>
        </div>
  
      </div>
  
      <!-- Texte bas du footer -->
      <p class="text-center text-gray-400 mt-10 text-sm">
        © 2025 ActuFoot360-V2 – Tous droits réservés.
      </p>
    </footer>
  </template>
  