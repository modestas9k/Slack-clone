<template>
    <section class="first-section">
        <header>
            <h1>Slack is your digital HQ</h1>
            <p>Transform the way you work with one place for everyone and everything you need to get stuff done.</p>
            <div class="buttons">
                <button class="btn-try">Try for free</button>
                <button class="btn-google">Sign up with google</button>
            </div>
        </header>
        <div class="img-wrapper">
            <img class="img-hero" src="./../assets/img-campaign-hero@2x.jpg" alt="chatExample">
        </div>
    </section>
    <section class="second-section">
        <div class="logos">
            <div class="logo-wrapper">
                <a href="_blank">
                    <img src="../assets/fox@2x.png" alt="fox">
                </a>
            </div>
            <div class="logo-wrapper">
                <a href="_blank">
                    <img src="../assets/lonelyplanet@2x.png" alt="flonelyplanet">
                </a>
            </div>
            <div class="logo-wrapper">
                <a href="_blank">
                    <img src="../assets/intuit@2x.png" alt="intuit">
                </a>
            </div>
            <div class="logo-wrapper">
                <a href="_blank">
                    <img src="../assets/carvana@2x.png" alt="carvana">
                </a>
            </div>
            <div class="logo-wrapper">
                <a href="_blank">
                    <img src="../assets/kiva@2x.png" alt="kiva">
                </a>
            </div>
            <div class="logo-wrapper">
                <a href="_blank">
                    <img src="../assets/target-logo@2x.png" alt="target">
                </a>
            </div>
            <div class="logo-wrapper">
                <a href="_blank">
                    <img src="../assets/devacurl@2x.png" alt="devacurl">
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
    .first-section {
        display: grid;
        flex-direction: column;
        background: #f6efe8;
        color: black;
        padding: 2rem;
    }
    header {
        display: flex;
        flex-direction: column;
        width: 100%;
    }
    h1 {
        font-weight: 700;
        font-size: 2.75rem;
        line-height: 2.75rem;
        margin-bottom: 16px;
    }
    p {
        font-size: 1.125rem;
        margin-bottom: 32px;
    }
    .buttons {
        display: flex;
        flex-direction: column;
        gap: 16px;
    }
    button {
        width: 100%;
        color: #FFFFFF;
        font-size: 16px;
        text-transform: uppercase;
        font-weight: 700;
        border-radius: 4px;
        border: none;
        cursor: pointer;
    }
    .btn-try {
        padding: 19px 40px 20px 40px;
        background: #611f69;
    }
    .btn-try:hover {
        background: #4a154b;
    }
    .btn-google {
        background: #1264a3;
        padding: 20px 40px;
    }
    .img-hero {
        width: 100%;
        height: auto;
        margin-top: 16px;
    }
    .second-section {
        background: #f6efe8;
        padding: 2rem;
    }
    .logos {
        display: flex;
        width: 100%;
        flex-wrap: wrap;
        justify-content: space-around;
        align-items: center;
    }
    .logo-wrapper {
        max-width: 170px;
        margin: 10px;
        text-align: center;
    }
    img {
        width: 100%;
    }
    
    @media (min-width: 768px) {
        section {
            grid-template-columns: 1fr 1fr;
            gap: 16px;
        }
        .img-hero {
            margin-top: 0px;
        }
    @media (min-width: 1024px) {
        h1 {
            font-size: 4rem;
            line-height: 1.1;
        }
    }
    @media (min-width: 1173px) {
        .buttons {
            flex-direction: row;
        }
    }
}
</style>