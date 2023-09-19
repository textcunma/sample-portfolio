<template>
     <div id="works">
          <p class="headline">WORKS</p>
          <div class="grid sm:grid-cols-1 lg:grid-cols-2 gap-4 md:gap-6">
               <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md">
                    <img class="rounded-t-lg object-cover h-48 w-96" src="@/assets/deepbeyond.png" alt="Deep Beyond画像" loading=”lazy” />
                    <div class="p-5">
                         <p class="mb-2 text-xl tracking-tight">○○○</p>
                         <p class="mb-3 font-normal text-gray-700">ソフトウェア</p>
                         <router-link to="/products/#deepbeyond">
                              <p class="normal-btn">
                                   Read more
                                   <ArrowSVG class="fill-gray-100"/>
                              </p>
                         </router-link>
                    </div>
               </div>
          </div>
     </div>
</template>

<script>
     import ArrowSVG from "@/components/ArrowSVG.vue";

     export default {
          components: { ArrowSVG }
     };
</script>