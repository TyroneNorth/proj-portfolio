<script setup lang="ts">
import { ref } from 'vue';

const text = ref('');

function onInput(e: any) {
  text.value = e.target.value;
}


//JavaScript for disabling form submissions if there are invalid fields
(function () {
  'use strict'

  // Fetch all the forms we want to apply custom Bootstrap validation styles to
  var forms = document.querySelectorAll('.needs-validation')

  // Loop over them and prevent submission
  Array.prototype.slice.call(forms)
    .forEach(function (form) {
      form.addEventListener('submit', function (event: { preventDefault: () => void; stopPropagation: () => void; }) {
        if (!form.checkValidity()) {
          event.preventDefault()
          event.stopPropagation()
        }
        alert('submitted');

        form.classList.add('was-validated')
      }, false)
    })
})()

const label = 'Submit';

</script>

<template>
    <form class="row g-3">
  <div class="col-md-4">
    <label for="validationDefault01" class="form-label">First name</label>
    <input type="text" class="form-control" id="validationDefault01" value="Tyrone" required>
  </div>
  <div class="col-md-4">
    <label for="validationDefault02" class="form-label">Last name</label>
    <input type="text" class="form-control" id="validationDefault02" value="North" required>
  </div>
  <div class="col-md-4">
    <label for="validationDefaultUsername" class="form-label" >Email</label>
    <div class="input-group">
      <span class="input-group-text" id="inputGroupPrepend2">@</span>
      <input type="text" class="form-control" id="validationDefaultUsername" value="Northwill.solutions@gmail.com"  aria-describedby="inputGroupPrepend2" required>
    </div>
  </div>
  <div >
  <div class="col">
    <textarea class="form-control" :value="text" @input="onInput" aria-label="With textarea"></textarea>
  </div>
  
  </div>
  
  <div class="col-12">
   
  </div>
  <div class="col-12">
    <a href="mailto:northwill.solutions@gmail.com" label='Send Email' class="std-btn" type="Submit" body="{{text}}">Send Email</a>

  </div>
</form>
</template> 

<style>

</style>