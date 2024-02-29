<template>
  <header>
        <h1>Örnek Proje</h1>
    </header>

    <nav>
        <RouterLink to="/">Ana Sayfa</RouterLink>
        <RouterLink to="/hakkimizda">Hakkımızda</RouterLink>
        <RouterLink to="/hizmetlerimiz">Hizmetlerimiz</RouterLink>
        <RouterLink to="/iletisim">İletişim</RouterLink>
    </nav>
</template>

<style scoped lang="scss">
    header {
        background-color: #333;
        color: #fff;
        padding: 10px;
        text-align: center;
    }

    nav {
        background-color: #555;
        padding: 10px;
        text-align: center;
        a {
            color: #fff;
            text-decoration: none;
            padding: 10px;
            margin: 0 10px;
        }
    }

</style>
