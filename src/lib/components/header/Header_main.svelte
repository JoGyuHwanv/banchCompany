<style >
    h1 {
        display: inline-block;
        vertical-align: middle;
        margin: 0.5rem;
        padding: 0;    
    }
    .headerBanch {
        color:rgb(255, 0, 183);
    }
    .headerCompany {
        color: black;
    }
    nav {
        display: inline-block;
        vertical-align: middle;
        float: right;
        height: 100%;
        line-height: 20px;
        position: absolute;
        right: 100px;
        top: 54%;
        transform: translateY(-50%);
    }

    ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
    }
    li.icon {
        flex-basis: 25%;
    }
    header {
        background: rgb(255, 255, 255);
        padding: 5px;
    }

    a {
        display: block;
        text-align: center;
        margin: .25rem;
        padding: .5rem 1rem;
        text-decoration: none;
        font-weight: bold;
        color: rgb(0, 0, 0);
        font-family: 'Montserrat Alternates', sans-serif;
        border-width: 0;
        border-style: solid;
    }

    a:hover {
        background: rgb(255, 255, 255);
    }

</style>
<script>
</script>
<header>
    <h1><a href="/"><span class="headerBanch">Banch</span><span class="headerCompany">&nbsp;Company</span></a></h1>
    <nav>
        <ul>
            <li><a href="/home">ABOUT</a></li>
            <li><a href="/project">PROJECT</a></li>
            <li><a href="/service">CONTEXT</a></li>
            <li><a href="/phone">TELEPHONE</a></li>
        </ul>
    </nav>
    
</header>