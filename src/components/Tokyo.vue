<template>
 <header>
          <h3 class="p-1 font-bold leading-none text-gray-800">TOKYO</h3>
        </header>

        <ul>
          <li class="card">
            <figure class="flex items-center max-h-52 sm:max-h-36 border-b border-gray-200 overflow-hidden rounded-t">
              <img src="../assets/godzilla.jpg" alt="">
            </figure>
            <div class="p-3">
              <aside class="flex mb-1.5">
                <span class="w-8 h-2 mr-2 rounded-full bg-red-400"></span>
              </aside>
              <p>
                GODZILLA potriasť jej packou zagratulovať k povýšeniu
              </p>
            </div>
            </li>
          <li class="card">
            <div class="p-3">
              <p>
                VAMPIRE CAFÉ suck my blood pls
              </p>
            </div>
          </li>
          <li class="card">
            <figure class="flex items-center max-h-52 sm:max-h-36 border-b border-gray-200 overflow-hidden rounded-t">
              <img src="../assets/hachiboy.png" alt="">
            </figure>
            <div class="p-3">
              <p>
                HACHIKO pohladkať tohto veľmi dobrého chlapca
              </p>

              <footer class="flex mt-2">
                <a class="px-1 py-0.5 mr-1.5 text-xs text-white bg-gray-500 bg-opacity-50 hover:bg-opacity-100 rounded" href="#">very</a>
                <a class="px-1 py-0.5 mr-1.5 text-xs text-white bg-gray-500 bg-opacity-50 hover:bg-opacity-100 rounded" href="#">good</a>
                <a class="px-1 py-0.5 mr-1.5 text-xs text-white bg-gray-500 bg-opacity-50 hover:bg-opacity-100 rounded" href="#">pes</a>
              </footer>
            </div>
          </li>

          <footer>
            <a href="#" class="hidden p-1 text-gray-500 hover:text-gray-700">
              Add new card...
            </a>

            <form action="">
              <textarea class="outline-none w-full border-t border-l border-gray-300 p-3 rounded shadow-inner" rows="3"></textarea>

              <div class="flex mt-1.5 items-center">
                <button class="btn btn-green">Add card</button>

                <a class="ml-0.5 p-1 text-gray-500 hover:text-gray-700" href="#">
                  <svg class="w-6 h-6 fill-current" viewBox="0 0 20 20">
                    <path
                      d="M15.898,4.045c-0.271-0.272-0.713-0.272-0.986,0l-4.71,4.711L5.493,4.045c-0.272-0.272-0.714-0.272-0.986,0s-0.272,0.714,0,0.986l4.709,4.711l-4.71,4.711c-0.272,0.271-0.272,0.713,0,0.986c0.136,0.136,0.314,0.203,0.492,0.203c0.179,0,0.357-0.067,0.493-0.203l4.711-4.711l4.71,4.711c0.137,0.136,0.314,0.203,0.494,0.203c0.178,0,0.355-0.067,0.492-0.203c0.273-0.273,0.273-0.715,0-0.986l-4.711-4.711l4.711-4.711C16.172,4.759,16.172,4.317,15.898,4.045z">
                    </path>
                  </svg>
                </a>
              </div>
            </form>
          </footer>
        </ul>
</template>

<script setup>
import { ref } from 'vue';
</script>
