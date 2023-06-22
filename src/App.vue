<script setup>
import navbar from './components/navbar.vue'
import hero from './components/Hero.vue'
import about from './components/about.vue'
import features from './components/features.vue'
import deep_dive from './components/deep_dive.vue'
import letscall_action from './components/letscall_action.vue'
import footers from './components/footers.vue'

</script>

<template >
<header>
 <img src="src/assets/bg-leaves.svg" class="absolute inset-0 object-cover w-full h-[500px] overflow-visible" alt="" />
   <navbar />
</header>
<section >
    <hero/>
    <about/>
    <features/>
    </section>
    <section>
      <deep_dive />
         <letscall_action />
    </section>
<footers />
   

    
</template>

