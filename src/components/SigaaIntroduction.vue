<template>
    <section class="introduction">
        <h2>Para iniciar é importante que você entenda que o sigaa é a base de tudo, por isso lembre-se dessas 3 coisas</h2>
        <div class="cards">
        <div class="card">
            <img src="@/assets/mobile-icon.png" alt="IFAL Mobile" />
            <p>Baixe o app IFAL MOBILE ou você não entra no Ifal</p>
        </div>
        <div class="card">
            <img src="@/assets/computer-icon.png" alt="Modo Clássico" />
            <p>Mexa no Sigaa só após clicar na opção "Modo Clássico"</p>
        </div>
        <div class="card">
            <img src="@/assets/coffee-icon.png" alt="Estresse" />
            <p>Por mais que você seja PHD em Sigaa, saiba que nunca será o suficiente, você vai sempre se estressar</p>
        </div>
        </div>
    </section>
</template>

<style>
.introduction {
  margin-top: 20px;
  background-color: #fff;
  border-radius: 8px;
  padding: 20px;
}

.introduction h2 {
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
  width: 27%;
}

.card img {
  width: 50px;
  margin-bottom: 10px;
}

.card p {
  font-size: 1em;
}

@media (max-width: 768px) {
  .card {
    flex: 1 1 100%; /* As cartas ocupam 100% da largura disponível */
    min-width: 50%; /* A largura mínima é 100% */
  }

  .cards {
    flex-direction: column; /* As cartas são empilhadas verticalmente */
    justify-content: space-between;
    align-items: center;
    gap: 10px;
  }
}

@media (max-width: 480px) {
  .card img {
    width: 40px; /* Reduz o tamanho da imagem em telas muito pequenas */
  }

  .card p {
    font-size: 0.9em; /* Ajusta o tamanho da fonte para telas muito pequenas */
  }
}
</style>