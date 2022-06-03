<template>
<form @submit.prevent="submitForm">
<label> Name:  </label>
<input type="name" required v-model= "name"/>

<label> Surname:  </label>
<input type="surname" required v-model= "surname"/>

<label> Desired course:  </label>
<input type="Dcourse" required v-model= "Dcourse"/>

<div class="submit">
<button> Register </button>
</div>
</form>

</template>

<script>

</script>

<style>


</style>