<template>

  <main class="flex bg-purple-500 h-screen lg:bg-gradient-to-r from-red-400 to-pink-400">
    <div class="sm:flex items-start w-screen px-4 py-10 overflow-x-auto">
      <!-- <div id="overlay" class="fixed top-0 left-0 w-full h-screen bg-black bg-opacity-70 z-10"></div> -->

      <!-- BOARD GAMEs -->

      <section class="list">
        <BoardGames />
      </section>


      <!-- TOYKO -->

      <section class="list">
        <Tokyo />
      </section>

      <!-- BRAIN THROUGHT -->

      <section class="list">
        <Brain />
      </section>

      <!-- NEW FORMULAR -->
      <Formular />

    </div>
  </main>

  <!-- PLAYGROUND -->
	<div
		class="min-h-screen lg:bg-teal-500 lg:bg-none bg-gradient-to-r from-red-400 to-pink-400 py-6 flex flex-col justify-center sm:py-12">
		<div class="relative py-3 sm:max-w-xl sm:mx-auto">
			<div
				class="absolute inset-0 bg-gradient-to-r lg:from-yellow-300 lg:to-pink-400 from-teal-400 to-blue-400 shadow-lg transform -skew-y-6 sm:skew-y-0 sm:-rotate-6 sm:rounded-3xl">
			</div>
			<div class="relative px-4 py-10 bg-white shadow-lg sm:rounded-3xl sm:p-20">
				<div class="max-w-md mx-auto">
					<div>
						<img src="https://secondhandsongs.com/picture/246305" alt="vašislav patejdlistan" class="h-7 sm:h-20 mx-auto rounded" />
					</div>
					<div class="divide-y divide-gray-200">
						<div class="py-8 text-base leading-6 space-y-4 text-gray-700 sm:text-lg sm:leading-7">
							<p>An advanced online playground for Tailwind CSS, including support for things like:</p>
							<ul class="list-disc space-y-2">
								<li class="flex items-start">
									<span class="h-6 flex items-center sm:h-7">
										<svg class="flex-shrink-0 h-5 w-5 text-teal-500" viewBox="0 0 20 20" fill="currentColor">
											<path fill-rule="evenodd"
												d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
												clip-rule="evenodd" />
										</svg>
									</span>
									<p class="ml-2">
										Customizing your
										<code class="text-sm font-bold text-gray-900">tailwind.config.js</code> file
									</p>
								</li>
								<li class="flex items-start">
									<span class="h-6 flex items-center sm:h-7">
										<svg class="flex-shrink-0 h-5 w-5 text-teal-500" viewBox="0 0 20 20" fill="currentColor">
											<path fill-rule="evenodd"
												d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
												clip-rule="evenodd" />
										</svg>
									</span>
									<p class="ml-2">
										Extracting classes with
										<code class="text-sm font-bold text-gray-900">@apply</code>
									</p>
								</li>
								<li class="flex items-start">
									<span class="h-6 flex items-center sm:h-7">
										<svg class="flex-shrink-0 h-5 w-5 text-teal-500" viewBox="0 0 20 20" fill="currentColor">
											<path fill-rule="evenodd"
												d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
												clip-rule="evenodd" />
										</svg>
									</span>
									<p class="ml-2">Code completion with instant preview</p>
								</li>
							</ul>
							<p>Perfect for learning how the framework works, prototyping a new idea, or creating a demo to share
								online.
							</p>
						</div>
						<div class="pt-6 text-base leading-6 font-bold sm:text-lg sm:leading-7">
							<p>Want to dig deeper into Tailwind?</p>
							<p>
								<a href="https://tailwindcss.com" class="text-teal-600 hover:text-teal-700"> Read the docs &rarr; </a>
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

</template>

<script setup>
import { ref, TriggerOpTypes } from 'vue';

import BoardGames from './components/BoardGames.vue';
import Brain from './components/Brain.vue';
import Tokyo from './components/Tokyo.vue';
import Formular from './components/Formular.vue';


</script>