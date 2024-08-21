<template>
    <section class="contacts    ">
        <h2>COISAS IMPORTANTES PARA SABER SOBRE O PLANO DE PROJETO DE CURSO</h2>
        <div class="cards">
            <div class="card">
                <img src="@/assets/dev.png" alt="Modo Clássico" />
                <h3>Faça estágio o quanto antes</h3>
            </div>
            <div class="card">
                <img src="@/assets/pencil.png" alt="Estresse" />
                <h3>Entre em projetos de pesquisa ou extensão</h3>
            </div>
            <div class="card">
                <img src="@/assets/hat.png" alt="Estresse" />
                <h3>Escolhas as matérias de forma consciente</h3>
            </div>
            <div class="card">
                <img src="@/assets/book.png" alt="Estresse" />
                <h3>Tenha um bom CRA</h3>
                <p>(Coeficiente de Rendimento Acadêmico)</p>
            </div>
        </div>
    </section>
</template>

<style scoped>
.contacts {
  margin-top: 20px;
  margin-bottom: 20px;
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
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.card img {
  width: 70px;
  margin-bottom: 10px;
}

.card p {
  font-size: 1em;
}
</style>