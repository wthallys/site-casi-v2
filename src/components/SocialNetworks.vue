<template>
    <section class="networks">
        <h2>Redes sociais que você precisa ter</h2>
        <div class="icons">
            <a href="https://www.linkedin.com/" target="_blank">
                <div class="icon">
                    <img src="@/assets/linkedin.png" alt="Linkedin" />
                </div>
            </a>
            <a href="https://github.com/" target="_blank">
                <div class="icon">
                    <img src="@/assets/github.png" alt="Github" />
                </div>
            </a>
        </div>
    </section>
</template>

<style scoped>
.networks {
  margin-top: 20px;
  background-color: #fff;
  border-radius: 8px;
  padding: 20px;
}

.networks h2 {
  text-align: center;
  margin-bottom: 20px;
}

.icons {
  display: flex;
  justify-content: space-around;
}

.icon {
  background-color: #FFBF30;
  padding: 10px;
  text-align: center;
  border-radius: 50%;
  width: 90px;
  height: 90px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.icon img {
  width: 50px;
  margin-bottom: 10px;
}

.icon p {
  font-size: 1em;
}
</style>