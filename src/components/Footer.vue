<template>
    <footer>
        <div class="footer-links">
            <RouterLink to="/">Ana Sayfa</RouterLink>
            <RouterLink to="/hakkimizda">Hakkımızda</RouterLink>
            <RouterLink to="/hizmetlerimiz">Hizmetlerimiz</RouterLink>
            <RouterLink to="/iletisim">İletişim</RouterLink>
        </div>
        <div class="footer-text">
            &copy; 2024 Örnek Proje. Tüm hakları saklıdır.
        </div>
    </footer>
</template>

<style scoped lang="scss">
        footer {
            position: fixed;
            bottom: 0;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .footer-links {
            background-color: #333;
            padding: 10px;
            width: 100%;
            text-align: center;
            a {
                color: #fff;
                text-decoration: none;
                margin: 0 10px;
            }
        }
        .footer-text {
            background-color: #fff;
            padding: 10px;
            width: 100%;
            text-align: center;
        }
</style>