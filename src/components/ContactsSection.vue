<template>
    <section class="contacts    ">
        <h2>Quem são seus aliados? Aqui vão alguns contatos importantes</h2>
        <div class="cards">
        <div class="card">
            <img src="@/assets/logo_casi.png" alt="IFAL Mobile" />
            <h3>DAA</h3>
            <p>sla@ifal.edu.br</p>
        </div>
        <div class="card">
            <img src="@/assets/logo_casi.png" alt="Modo Clássico" />
            <h3>Coordenação</h3>
            <p>sla@ifal.edu.br</p>
        </div>
        <div class="card">
            <img src="@/assets/logo_casi.png" alt="Estresse" />
            <h3>Bar da frente</h3>
            <p>Uma ótima opção</p>
        </div>
        <div class="card">
            <img src="@/assets/logo_casi.png" alt="Estresse" />
            <h3>DEE</h3>
            <p>sla@ifal.edu.br</p>
        </div>
        <div class="card">
            <img src="@/assets/logo_casi.png" alt="Estresse" />
            <h3>CREE</h3>
            <p>sla@ifal.edu.br</p>
        </div>
        </div>
    </section>
</template>

<style scoped>
.contacts {
  margin-top: 20px;
  background-color: #fff;
  border-radius: 8px;
  padding: 20px;
}

.contacts h2 {
  text-align: center;
  margin-bottom: 20px;
}

.cards {
  display: flex;
  justify-content: space-between;
}

.card {
  background-color: #ffe0b2;
  padding: 20px;
  text-align: center;
  border-radius: 30px;
  width: 170px;
  height: 210px;
}

.card img {
  width: 70px;
  margin-bottom: 10px;
}

.card p {
  font-size: 1em;
}
</style>