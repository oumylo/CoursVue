<script setup>

const montant=2000;
const annee=new Date().getFullYear();
const prime = 0.5;
const person = {fullName: "Oumou Néné", role: "Dev Full stack"}

</script>
<template>
  <section class="card">
    <div>
        <h2>Mes informations</h2>
        <ul>
            <li>Nom : {{ person.fullName }}</li>
            <li>Rôle : {{ person.role }}</li>
            <li>Montant : {{ montant.toLocaleString() }} Fcfa</li>
            <li>Année : {{ annee }}</li>
            <li>Salaire : {{ montant + montant*prime }}</li>

        </ul>
    </div>
  </section>
</template>


<style scoped>
.card{
    padding: 16px;
    border: 1px solid #eee;
    border-radius: 12px;
}

.box{
    margin-top: 10px;
    padding: 12px;
    border: 1px dashed #ccc;
    border-radius: 10px;
}

</style>