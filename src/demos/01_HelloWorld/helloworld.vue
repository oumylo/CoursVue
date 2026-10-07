<script setup>

const message = "Néné Yayam ";

</script>

<template>
  <section class="card">
    <h2> Hello World </h2>
    <p>Premier Composant Vue(SFC)</p>
    <div class="box">
        <strong>Message:</strong>{{message.toLocaleUpperCase()}}
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