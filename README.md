# notas-estudo
informações técnico em informática

markdown



## configurando Git 

Para utilizar o git na minha maquina  eu preciso configurar determinados comandos,sendo eles 

''' bash
git config --global 
'''
## como configurar GitHub
Instale o Git,logo em seguida abra o CMD,terminal de comandos,Shell ou PowerShell Digite git -version

C:\user/ seu nome Ponick>git --version
git version 2.37.1.windows.1

configure também o seu git local,com os seguintes comandos:

git config --global use.name "seu nome"
git config --global user.email "seuEmail@gmail.com"

Após fazer isso, crie sua conta no site oficial no github
    https://github.com/
## SSH - como configurar  a maquina para GitHub 

## como criar um repositorio 
 // __________________________________ PRIMEIRA PARTE _______________________________________________________________

 <h2> Avaliação</h2>

    <button id="questao1">Questão 1</button>
    
    <script src="./scripts/avaliacao.js"></script>
 
 // _______________________________ SEGUNDA PARTE _______________________________________________________________________
// function
//getElementById
//addEventListener

//-----------------------QUESTÂO 1 ---------------------------------------
function exemplo1 () {
    //ESCREVE O ENUNCIADO AQUI
    // SOME 2 NÚMEROS 
    alert ("funcionou aqui")
    const numero = Number(prompt("Digite um numero:"))
    const numero2 = Number(prompt ("Digite outro numero:"))
    alert( numero+numero2)
}
const buttonexemplo1 = document.getElementById("questao1")
buttonexemplo1.addEventListener('click', () => { exemplo1() })

