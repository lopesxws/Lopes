
body>
    <header>ALURAFLIX</header>

    <section>
    <section class="chamada">
        <div class="chamada-texto">
            <h1>ATRAVÉS DO ARANHAVERSO</h1>
            <p>#homem-aranha</p>
@@ -27,6 +27,27 @@ <h1>ATRAVÉS DO ARANHAVERSO</h1>
        </div>
    </section>

    <section class="categoria">
        <h2>Filmes e séries</h2>
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=cs15QqG6Gjc">
                <img src="https://img.youtube.com/vi/cs15QqG6Gjc/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=nCmIwcycUJ8">
                <img src="https://img.youtube.com/vi/nCmIwcycUJ8/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=FvRmEapoHRc">
                <img src="https://img.youtube.com/vi/FvRmEapoHRc/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=Ipkw_hWW-Hw">
                <img src="https://img.youtube.com/vi/Ipkw_hWW-Hw/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=d4DzMNGoyis">
                <img src="https://img.youtube.com/vi/d4DzMNGoyis/maxresdefault.jpg" />
            </a>
        </div>
    </section>
</body>

</html>
‎styles.css
+16
-1
Original file line number	Diff line number	Diff line change
@@ -12,7 +12,7 @@ header {
    color: rgb(42, 122, 228);
}

section {
.chamada {
    background: rgb(184, 156, 213);
    padding-bottom: 80px;
    padding-top: 80px;
@@ -30,4 +30,19 @@ h1 {

p {
    font-size: 20px;
}
img {
    height: 200px;
}
.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
}
.categoria {
    padding-left: 20px;
    padding-right: 20px;
}
