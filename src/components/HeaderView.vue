<template>
    <header class="bg-black shadow-md py-8 px-20">
       <nav class="flex justify-between">
        <div class="flex items-center gap-2">
            <img src="/actufootv2.png" alt="Football News" class="w-20 h-20">
        </div>
            <ul class="flex items-center gap-6 font-medium">
                <li>
                    <router-link to="/" class="text-white hover:text-red-500">Accueil</router-link>
                </li>
                <li>
                    <router-link to="/stats" class="text-white hover:text-red-500">Statistiques</router-link>
                </li>
            </ul>
       </nav>
    </header>
</template>