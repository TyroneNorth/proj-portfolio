<script setup lang="ts">
// @ is an alias to /src
import StdButton from './Button.vue';

import { ref } from 'vue';
import Waves from './Waves.vue';
import Footer from './Footer.vue';







</script>

<template>
  <Waves />
<div class="container">
  <div id="avadaka"  class="row">
      <div class="col-sm-12 col-lg-9 ccard">
        <img src="../assets/images/avadaka.png" alt="Avadaka" class="img-fluid" />
      </div>
      <div class="col-sm-12 col-lg-3">
        <h1 class="text-center">Avadaka Web Builder</h1>
        <p class="text-center">
          <span>Product Landing Pageg for popular web builder.</span>
          <!-- SIte Info-->
          <br />
        
           
        <ul class="tech rounded ccard">
          
          <a target="_blank" href="https://vuejs.org/" class="list-group-item list-group-item-action active" aria-current="true">Vue 3</a>
          <a target="_blank" href="https://vitejs.dev/" class="list-group-item list-group-item-action">Vite</a>
          <a target="_blank" href="https://quasar.dev/" class="list-group-item list-group-item-action">Quasar</a>
  
          </ul>
          
        
        <a class="outline-btn" target="_blank" href="https://avadaka.vercel.app/">See live</a>
        <a class="ghost-btn" target="_blank" href="https://github.com/TyroneNorth/Avadaka">Source</a>
        </p>
      </div>
    </div>
    <div class="border-bottom"></div>

<div id="task_away"  class="row">
      <div class="col-sm-12 col-lg-9 ccard">
        <img src="../assets/images/task_away.png" alt="Task Away" class="img-fluid" />
      </div>
      <div class="col-sm-12 col-lg-3">
        <h1 class="text-center">Task Away</h1>
        <p class="text-center">
          <span>Todo/Task List PWA </span>
          <!-- SIte Info-->

          A Full-Stack CRUD application with User Authenticatoin and Authorization Management.
          <br />
        <ul class="tech rounded ccard">
          <li>
            <a target="_blank" href="https://vuejs.org/" class="list-group-item list-group-item-action active" aria-current="true">
            Vue 3
            </a>
          </li>
          <a target="_blank" href="https://quasar.dev/" class="list-group-item list-group-item-action">Quasar</a>
          <a target="_blank" href="https://vitejs.dev/" class="list-group-item list-group-item-action">Vite</a>
          <a target="_blank" href="https://supabase.com/" class="list-group-item list-group-item-action">Supabase</a>
          <a target="_blank" href="https://www.postgresql.org/" class="list-group-item list-group-item-action">PostGresSQL</a>
          <a target="_blank" href="https://www.typescriptlang.org/" class="list-group-item list-group-item-action">Typescript</a>
  
          </ul>
          
        
        <a class="outline-btn" target="_blank" href="https://task-away-pwa.vercel.app/">See live</a>
        <a class="ghost-btn" target="_blank" href="https://github.com/TyroneNorth/Task-Away">Source</a>
        </p>
      </div>
    </div>
    <div class="border-bottom"></div>

  
    <div id="mega"  class="row">
      <div class="col-sm-12 col-lg-9 ccard">
        <img src="../assets/images/mega_fusion.png" alt="Mega Fusion" class="img-fluid" />
      </div>
      <div class="col-sm-12 col-lg-3">
        <h1 class="text-center">Mega Fusion</h1>
        <p class="text-center">
          <span>E-commerce Landing Page</span>
          <!-- SIte Info-->
          <br />
        
            Mega Fusion has ambitions to be the first commercially viable nuclear fusion energy solution.
            Technoologies:
        <ul class="tech rounded ccard">
          <li>
            <a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/HTML" class="list-group-item list-group-item-action active" aria-current="true">
            HTML
            </a>
          </li>
          <a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/CSS" class="list-group-item list-group-item-action">CSS</a>
          <a target="_blank" href="https://www.javascript.com/" class="list-group-item list-group-item-action">Javascript</a>
          <a target="_blank" href="https://www.w3schools.com/w3css/defaulT.asp" class="list-group-item list-group-item-action">W3.CSS</a>
  
          </ul>
          
        
        <a class="outline-btn" target="_blank" href="https://megafusion.vercel.app/">See live</a>
        <a class="ghost-btn" target="_blank" href="https://github.com/TyroneNorth/Commerce">Source</a>
        </p>
      </div>
    </div>
    <div class="border-bottom"></div>

     <div id="eng" class="row">
      <div class="col-sm-12 col-lg-9  ccard">
        <img src="../assets/images/consult.png" alt="Engineering Consulting" class="img-fluid" />
      </div>
      <div class="col-sm-12 col-lg-3">
        <h1 class="text-center">Engineering Consulting</h1>
        <p class="text-center">
          <span>World Class contractors</span>
          <!-- SIte Info-->
          <br />
        
            We provide your business with the best insight, tools, and experts to get the job done right...the first time!
            Technoologies:
        <ul class="tech rounded ccard">
          <li>
            <a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/HTML" class="list-group-item list-group-item-action active" aria-current="true">
            HTML
            </a>
          </li>
          <a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/CSS" class="list-group-item list-group-item-action">CSS</a>
          <a target="_blank" href="https://www.javascript.com/" class="list-group-item list-group-item-action">Javascript</a>
          <a target="_blank" href="https://getbootstrap.com/" class="list-group-item list-group-item-action">Bootstrap</a>
  
          </ul>
          
        
        <a class="outline-btn" target="_blank" href="https://engsolutions.vercel.app/">See live</a>
        <a class="ghost-btn" target="_blank" href="https://github.com/TyroneNorth/Solutions">Source</a>
        
        </p>
        
      </div>
    </div>

    <div class="border-bottom"></div>

    <div id="rice" class="row">
     <div class="col-sm-12 col-lg-9  ccard">
        <img src="../assets/images/riceroll.png" alt="Mega Fusion" class="img-fluid" />
      </div>
      <div class="col-sm-12 col-lg-3">
      
        <h1 class="text-center">Rice & Rolls</h1>
        <p class="text-center">
          <span>An atmospheric Asian cuisine Restaurant</span>
          <!-- SIte Info-->
          <br />
        
            Authentic Asian Cuisine at a price that doesn't compromise on quality.
            Technoologies:
        <ul class="tech rounded ccard">
          <li>
            <a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/HTML" class="list-group-item list-group-item-action active" aria-current="true">
            HTML
            </a>
          </li>
          <a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/CSS" class="list-group-item list-group-item-action">CSS</a>
          <a target="_blank" href="https://www.javascript.com/" class="list-group-item list-group-item-action">Javascript</a>
          
  
          </ul>
          
        
        <a class="outline-btn" target="_blank" href="https://rice-n-rolls.vercel.app/index.html">See live</a>
        <a class="ghost-btn" target="_blank" href="https://github.com/TyroneNorth/RiceNRolls">Source</a>
        
        </p>
       
      </div>
     
    </div>

   

    

    <!-- Body-->

    <!--Footer-->
    <Footer />
  </div>
</template>

<style>

@media only screen and (max-width: 600px) {
    .std-btn {
        font-size: small;
    }
    .lrg-btn {
        font-size: large;
    }
    .sml-btn {
        font-size: small;
    }
    .outline-btn {
        font-size: small;
    }
    .ghost-btn {
        font-size: small;
    }
}


.tech {
  list-style-type: none;
  margin-bottom: 2;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

.ccard {
  background-color: transparent;
  border-radius: 4px;
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
 
  margin-bottom: 2em;
  transition: all 0.3s ease-in-out;

}

.ccard:hover {
  box-shadow: 16px 16px 32px rgba(0, 0, 0, 0.2);
  border: 1px solid var(--primary-color);
}

.border-bottom {
  border: 1px solid transparent;
  margin-bottom: 1.5rem;
  margin-top: 1.5rem;
}

a.std-btn {
    padding: 0.5em 1em;
    border-radius: 4px;
    font-size: 1em;
    text-align: center;
    color: white;;
    border: none;
    cursor: pointer;
    transition: all 0.4s ease-in-out;
    width: 100%;
    max-width: 100px;
    height: auto;
    box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
    background-color: var(--background-color-primary);
    text-decoration: none;
}

a.std-btn:hover {

   color: white;

    }

</style>

