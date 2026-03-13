<script>
    import github_logo from '$lib/assets/github-logo.svg';
</script>

<div class="header">
    <p id="logo">Labra</p>
    <div class="login">
        <button id="logintxt"><a href="http://localhost:8080/login">
            <img src={github_logo} alt="github logo" height="32" width="32" />
            Login with Github
        </a></button>
    </div>
</div>
<hr>
<slot />

<style>
    .header {
        background-color: var(--bg-color);
        min-height: 7vh;
        color: var(--text-color);
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
        background-color: var(--crust);
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