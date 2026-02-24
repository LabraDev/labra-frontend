<script>
    
</script>

<div class="header">
    <p id="logo">Labra</p>
    <div class="login">
        <p>(pfp)</p>
        <p id="logintxt">Login</p>
    </div>
</div>
<hr>
<slot />

<style>
    .header {
        background-color: var(--bg-color);
        min-height: 7vh;
        color: white;
        width: 100%;
        display: flex;
        padding-top: 2vh;
    }
    #logo {
        margin-left: 3vh;
        font-size: 32px;
    }
    #logintxt {
        margin-left: 1vh;
        font-size: 20px;
    }
    .login {
        margin-left: auto;
        margin-right: 3vh;
        display: flex;
        justify-content: center;
    }
    hr {
        height: 0.2vh;
        border-width: 0;
        color: var(--hr-color);
        background-color: var(--hr-color);
    }
</style>