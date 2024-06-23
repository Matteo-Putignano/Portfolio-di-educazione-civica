<nav class="bar">
    <ul>
        <div class="botton"><a href="./"><li>Introduzione</li></a></div>
        <div class="botton"><a href="./italiano_e_storia"><li>Italiano e storia</li></a></div>
        <div class="botton"><a href="./informatica"><li>informatica</li></a></div>
        <div class="botton"><a href="./inglese"><li>inglese</li></a></div>
    </ul>
    <img id="logo_agnelli" src="./logo.jpg" alt="logo">
</nav>

<style>
    .bar {
        display: flex;
        justify-content:center;
        border-radius: 15px;
        width: 100%;
        height: 100px;
        background-color: lightgoldenrodyellow;
    }

    #logo_agnelli {
        width: 200px;
        height: 100px;
        border-radius: 20px;
        margin-top: 2px; 
    }

    .bar ul {
        width: 50%;
        display: flex;
        justify-content: right;
        font-size: 1.2vw;
    }

    .botton {
        background-color: black;
        border-radius: 5px;
        text-align: center;
        line-height: 250%;
        width: 10rem;
        font-weight: bold;
        margin-right: 3%;
    }

    .botton a {
        color: white;
        font-size: 1vw;
    }

    .botton:hover {
        background-color: white;
        border: 1px solid black;
        cursor: pointer;
    }

    .botton:hover a {
        color: black;
    }

</style>