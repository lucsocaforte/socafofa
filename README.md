# socafofa
<!DOCTYPE html>
<html lang="pt-br">








<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus objetivos do ano</title>
    <link rel="stylesheet" href="style.css">
</head>








<body>
    <section class="conteudo-principal">
        <h2 class="titulo-principal">CRUZEIRO<span>_</span></h2>
        <div class="conteudo">
            <div class="botoes">
                <button class="botao ativo">Tempo para o Cruzeiro Quitas suas dividas</button>
                <button class="botao">Treinar para ganhar algum titulo</button>
                <button class="botao">Contratar jogadores</button>
                <button class="botao">Tempo pra o Cruzeiro ganhar mais uma liberta</button>
            </div>
            <div class="abas-textos">
                <div class="aba-conteudo ativo">
                    <h3 class="aba-conteudo-titulo-principal">Quitar as dividas</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias0"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas0"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min0"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg0"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
                <div class="aba-conteudo">
                    <h3 class="aba-conteudo-titulo-principal">Treinar para ganhar mais uma</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias1"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas1"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min1"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg1"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
                <div class="aba-conteudo">
                    <h3 class="aba-conteudo-titulo-principal">Contratação</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias2"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas2"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min2"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg2"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
                <div class="aba-conteudo">
                    <h3 class="aba-conteudo-titulo-principal">Treinar para esmagar seus oponentes</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias3"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas3"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min3"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg3"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <script src="main.js"></script>
</body>
</html>











:root {
   --cor-de-fundo: #1E1E1E;
      --verde: #fcfcfc;
      --branco: #FFFFFF;
      --botao-ativo: #3A375E;
      --botao-inativo: rgba(58, 55, 94, 0.5);
      --texto-fundo: rgba(58, 55, 94, 0.3);
   }
  
  
  
  
   body {
      background-color: var(--cor-de-fundo);
      color: var(--branco);
      font-family: 'Chakra Petch', sans-serif;
   }
  
  
   .conteudo-principal {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      max-width: 1200px;
      width: 100%;
      margin: 0 auto;
   }
  
  
  
  
   .titulo-principal {
      text-align: left;
      width: 100%;
      font-size: 100px;
   }
  
  
  
  
   .titulo-principal span {
      color: var(--verde);
   }
  
  
  
  
  
  
  
  
   .botao {
      font-family: 'Chakra Petch', sans-serif;
      background-color: var(--botao-inativo);
      color: var(--branco);
      display: flex;
      justify-content: center;
      padding: 1em;
      font-size: 18px;
      align-items: center;
      width: 100%;
      border-bottom: 4px solid var(--botao-ativo);
      border-left: 2px solid var(--botao-ativo);
      border-right: 2px solid var(--botao-ativo);
      border-top: none;
   }
  
  
  
  
   .botao:first-child {
      border-radius: 40px 40px 0 0;
   }
  
  
  
  
   .botoes {
      display: block;
   }
  
  
  
  
   .botao.ativo{
      background-color: var(--botao-ativo);
      border-bottom: 4px solid var(--verde);
   }
  
  
  
  
   .abas-textos{
      background-color: var(--texto-fundo);
      padding: 40px;
      border-radius: 0 0 40px 40px;
   }
   .aba-conteudo.ativo{
      display:block;
   }
  
  
  
  
   .aba-conteudo{
      display: none;
   }
  
  
  
  
   .aba-conteudo-titulo-principal{
      font-size: 28px;
      text-align: center;
   }
   .aba-conteudo-titulo-secundario{
      text-align: center;
      color: var(--verde);
      text-transform: uppercase;
   }
  
  
  
  
   .contador{
      display:flex;
      justify-content: center;
      flex-wrap: wrap;
      align-items: center;  
   }
   .contador-digito{
      padding: 0 16px;
      text-align: center;
      min-width: 100px;
   }
  
  
  
  
   .contador-digito-numero{
      font-size: 80px;
      margin: 0;
  
  
  
  
   }
  
  
  
  
   .contador-digito-texto{
      color: var(--verde);
      font-size: 20px;
      margin: 0;
  
  
  
  
   }
  
  
  
  
   @media screen and (min-width: 768px) {
      .botoes {
          display: flex;
      }
  
  
  
  
      .botao:first-child {
          border-radius: 40px 0 0 0;
      }
  
  
  
  
      .botao:last-child {
          border-radius: 0 40px 0 0;
      }
   }
      
       body {
         background-image: url("data:image/jpeg;base64,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")
       }



const botoes = document.querySelectorAll(".botao");
const textos = document.querySelectorAll(".aba-conteudo");
















for (let i = 0; i < botoes.length; i++) {
  botoes[i].onclick = function () {
















      for (let j = 0; j < botoes.length; j++) {
          botoes[j].classList.remove("ativo");
          textos[j].classList.remove("ativo");
      }
















      botoes[i].classList.add("ativo");
      textos[i].classList.add("ativo");
  }
}
















const contadores = document.querySelectorAll(".contador");
const tempoObjetivo1 = new Date("2024-10-05T00:00:00");
const tempoObjetivo2 = new Date("2024-12-05T00:00:00");
const tempoObjetivo3 = new Date("2024-12-30T00:00:00");
const tempoObjetivo4 = new Date("2024-12-01T00:00:00");
















const tempos = [tempoObjetivo1,tempoObjetivo2,tempoObjetivo3,tempoObjetivo4];
































function calculaTempo(tempoObjetivo) {
  let tempoAtual = new Date();
  let tempoFinal = tempoObjetivo - tempoAtual;
  let segundos = Math.floor(tempoFinal / 1000);
  let minutos = Math.floor(segundos / 60);
  let horas = Math.floor(minutos / 60);
  let dias = Math.floor(horas / 24);
















  segundos %= 60;
  minutos %= 60;
  horas %= 24;
  if (tempoFinal > 0){
      return [dias,horas,minutos,segundos];
  } else {
      return [0,0,0,0];
  }
}
















function atualizaCronometro(){
  for (let i=0; i<contadores.length;i++){
      document.getElementById("dias"+i).textContent = calculaTempo(tempos[i])[0];
      document.getElementById("horas"+i).textContent = calculaTempo(tempos[i])[1];
      document.getElementById("min"+i).textContent = calculaTempo(tempos[i])[2];
      document.getElementById("seg"+i).textContent = calculaTempo(tempos[i])[3];
  }
}
















function comecaCronometro(){
  atualizaCronometro();
  setInterval(atualizaCronometro,1000);
}








comecaCronometro();



