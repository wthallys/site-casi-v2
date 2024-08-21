<template>
    <footer class="footer">
        <div class="logo">
            <img src="@/assets/logo_casi.png" alt="CASI ADA" width="90" height="90">
            <div class="logo-name">
                <h2>CASI ADA</h2>
                <p>Centro Acadêmico de Sistemas de Informação</p>
            </div>
        </div>
        <div class="contact">
            <a href="mailto:casistemas.ifal@gmail.com" target="_blank">
                <div class="icon">
                    <img src="@/assets/email.png" alt="Email" />
                </div>
            </a>
            <a href="https://github.com/" target="_blank">
                <div class="icon">
                    <img src="@/assets/whatsapp.png" alt="Whatsapp" />
                </div>
            </a>
        </div>
    </footer>
</template>

<style>
.footer {
    width: 98vw;
    background-color: #FFF;
    padding: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0px;
}

.logo {
    display: flex;
    flex-direction: row;
}

.logo-name {
    font-family: "Roboto Slab", serif;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.contact {
    width: 150px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
</style>