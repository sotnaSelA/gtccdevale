<template>
    <body>
        <div class="container">    
            <div class="workspace">
                <div class="head">DASHBOARD
                    <button class="btn-action">+</button>
                </div>
                <div class="search">
                <input class="input-search" type="search" placeholder="Buscar dados">
                    <input class="btn-default btn-search" type="button" value="Buscar">
                </div>
                <table border="1">
                    <tr class="table-title">
                        <td>Nome</td>
                        <td>Idade</td>
                        <td>Profissão</td>
                    </tr>
                    <tr>
                        <td>Ted</td>
                        <td>22</td>
                        <td>Estudante</td>
                    </tr>
                    <tr>
                        <td>Ralf</td>
                        <td>26</td>
                        <td>Designer</td>
                    </tr>
                </table>
      
            </div> 
        </div>
    </body>
</template>
  
<script>
    export default{
        name: 'DashBoard'
    }
</script>

<!-- <style>
    body{
      margin: 0;
      padding: 0;
    }

    .flex-dash{
        display: flex;
    }

    .container-dash{
        width: 100%;
        height: 100vh;
        background: #f8f8f8;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .flex-dash{
        width:750px;
        height: 450px;
        background-color: white;
        display: grid;
        align-items: top;
        justify-content: center;
        box-shadow: 0 0 1000px 0  #09a6a38e;
        display: flex;
        border-style: solid;
        border-color: #09a6a3;
    }

    .head-dash{
        background-color: #09a6a3;
        align-items: center;
        width: 100%;
        height: 35px;
        font-size: 30px;
        color: white; 
        font-family: "Poiret One", sans-serif;
        
        text-align: center;
    }

    .btn-action-dash{
        position: relative;
        background-color: #ffffff;
        border: #09a6a3 solid 1px;
        border-radius: 100px;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 35px;
        height: 35px;
        cursor: pointer;
        font-size: xx-large;
        color: #09a6a3;
        left: 633px;
        top: -19px;
    }
    .btn-action-dash:hover{
        background-color: #09a6a3;
        color: #ffffff;
        border-style: solid;
        border-color: #ffffff;
        border-width: 2px; 
    }

    .input-pesquisa-dash{
        width: 80%;
        margin: 5px 0;
    }
    
    
</style> -->