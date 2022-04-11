<template>
    <section>
        <header>
            <h1>Slack is your digital HQ</h1>
            <p>Transform the way you work with one place for everyone and everything you need to get stuff done.</p>
            <div class="buttons">
                <button class="btn-try">Try for free</button>
                <button class="btn-google">Sign up with google</button>
            </div>
        </header>
        <img class="img-hero" src="./../assets/img-campaign-hero@2x.jpg" alt="chatExample">
    </section>
</template>

<script>
export default {

}
</script>

<style>
    section {
        display: flex;
        flex-direction: column;
        background: #f6efe8;
        color: black;
        padding: 2rem;
    }
    header {
        display: flex;
        flex-direction: column;
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
        display: flex;
        width: 100%;
        height: 100%;
        margin-top: 16px;
    }
    
    @media (min-width: 768px) {
        section {
            flex-direction: row;
        }
        header {
            flex: 1;
        }
        img-hero {
            flex: 1;
        }

}
</style>