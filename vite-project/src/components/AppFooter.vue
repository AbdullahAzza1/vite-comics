<script></script>

<template>
    <footer>
        <div class="footer">
            <div class="footerContent">
                <div>
                    <div>
                        <h3>DC COMICS</h3>
                        <div>news</div>
                        <div>videos</div>
                        <div>games</div>
                        <div>tv</div>
                        <div>movies</div>
                        <div>comics</div>
                        <div>characters</div>
                    </div>
                    <h3>SHOP</h3>
                    <div>comics</div>
                    <div>characters</div>
                </div>
                <div>
                    <h3>DC</h3>
                    <div>news</div>
                    <div>videos</div>
                    <div>games</div>
                    <div>tv</div>
                    <div>movies</div>
                    <div>comics</div>
                    <div>characters</div>
                    <div>tv</div>
                    <div>movies</div>
                    <div>comics</div>
                    <div>characters</div>
                </div>
                <div>
                    <h3>SITES</h3>
                    <div>characters</div>
                    <div>tv</div>
                    <div>movies</div>
                    <div>comics</div>
                    <div>characters</div>
                </div>
            </div>
            <div>
                <img class="bgFooter" src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="BassFooter">
            <button>kasuhf</button>
            <div class="community">
                <div>FOLLOW US</div>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
            </div>
        </div>
    </footer>
</template>

<style scoped>
.footer {
    display: flex;
    background-image: url(../assets/img/footer-bg.jpg);
    height: 30rem;
    color: white;
    justify-content: space-between;
}

.footerContent {
    display: flex;
}

div {
    padding: 0 1rem;
}

.BassFooter {
    background-color: rgb(58, 57, 57);
    height: 7rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.community {
    display: flex;
    align-items: center;
}

.bgFooter {
    width: 40%;
    background-size: cover;
    background-position: center;
}
</style>