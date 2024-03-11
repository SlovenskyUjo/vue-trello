<template>
  <header>
          <h3 contenteditable="" class="p-1 font-bold leading-none text-gray-900 outline-none focus:shadow-outline">BRAIN THROUGHT</h3>
        </header>

        <ul>
          <li class="card">
            <div class="p-3">
              <p>
                Zvykol som byť mladší
              </p>
            </div>
          </li>  
          <li class="card">
            <div class="p-3">
              <p contenteditable="" class="outline-none focus:shadow-outline">
                nemám rád cestovanie. možno je to tým, že ma otec mlátil globusom
              </p>
            </div>
          </li>  
          <li class="card">
            <div class="p-3">
              <p>
                čo keby fitness ľudia prestali cvičiť a všetka krv sa im z bicepsov naleje do hlavy a každý z nich je hawking.
              </p>
            </div>
          </li>  
        </ul>

        <footer>
          <a class="hidden p-1 text-gray-500 hover:text-gray-700" href="#">
            Add a card..
          </a>
        </footer>
</template>

<script setup>
  import PopUp from './PopUp.vue';
</script>