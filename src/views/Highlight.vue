<script setup lang="ts">
import image from "@/assets/pi.jpg"
import IconLinked from "@/components/IconLinked.vue";
import Rating from "@/components/Rating.vue"
import Cloud from "@/components/Cloud.vue";
</script>

<template>
    <!-- TODO change bg-color / reverse gradiant-->
    <div class="bg-dark bg-gradient text-white">

      <div class="text-center">
        <img :src="image" width="200" class="rounded-circle p-2"/>
      </div>
      
      <IconLinked class="mt-1" icon="bi-house" value="59 avenue de la République 78800, Houilles"></IconLinked>    
      <IconLinked class="mt-1" icon="bi-telephone" link="tel:+33668315293" value="+33 6.68.31.52.93"></IconLinked>
      <IconLinked class="mt-1" icon="bi-envelope-at" link="mailto:lucas.pussacq@gmail.com" value="lucas.pussacq@gmail.com"></IconLinked>
      <IconLinked class="mt-1" icon="bi-github" link="https://github.com/lpussacq" value="github.com/lpussacq"></IconLinked>
      <IconLinked class="mt-1" icon="bi-linkedin" link="https://www.linkedin.com/in/lpussacq" value="linkedin.com/in/lpussacq"></IconLinked>

      <div class="m-2">
          <div class="d-flex">
            <div class="flex-grow-1">Français</div>
            <Rating :rate="5"></Rating>
        </div>
    
          <div class="d-flex">
            <div class="flex-grow-1">Anglais</div>
             <Rating :rate="4"></Rating>
        </div>
      </div>

      <Cloud class="text-center" spacing="p-2" text="text-white" color="bg-primary" :words="[
        'C#',
        'Javascript',
        'SQL',
        'HTML5',
        'CSS',
        '.NET Framework',
        '.NET Core',
        'VueJs',
        'AngularJs',
        'Azure',
        'Function App',
        'Git',
        'Web API',
        'DevOps',
        'Agile',
        'TDD',
        'BDD',
        'Clean Architecture',
      ]"></Cloud>
      <div>
        
      </div>
    </div>
</template>