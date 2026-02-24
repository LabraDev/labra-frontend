<script>
    
</script>

<slot />
<hr>
<div class="footer">
    <p>Labra Co.</p>
    <p>About</p>
    <p>Contact</p>
</div>

<style>
    .footer {
        background-color: var(--bg-color);
        min-height: 20vh;
        color: white;
        width: 100%;
        display: flex;
        align-items: center;
        flex-direction: column;
        padding-top: 2vh;
        margin: auto;
    }
    p {
        margin: 1vh;
    }
    hr {
        height: 0.2vh;
        border-width: 0;
        color: var(--hr-color);
        background-color: var(--hr-color);
    }
</style>