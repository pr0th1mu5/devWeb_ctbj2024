> [!note]
> Para ver como fica no navegador web, salve esse arquivo como .html

`Atenção` Esse código foi copiado inteiramente da prova para esse arquivo. É importante que você estude e entenda o código.
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Primeira Avaliação de Desenvolvimento Web</title>
 <style type="text/css">
    p.nomeEstudante{
        color:red;
    }
    p{
        font-size: 14px;
        line-height: 2px;
    }
    #ultimaQuestione .questione{
        color:red;
    }
    #questoes .questione{
        color:blue;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        font-size: 12px;
    }
 </style>
</head>
<body>
    <div id="wrapper">
        <div id="headerProva">
            <p>Ministério da Educação</p>
            <p>Universidade Federal do Piauí</p>
            <p>Coordenação de Informática</p>
            <p>Colégio Técnico de Bom Jesus</p>
            <p class="nomeEstudante">Nome: _________________________________
            <p>Nota:____</p>
            </p>
        </div>
        <hr />
        <div id="informacoes">
            <h5>
                Nenhuma forma de consulta é aceita.<br />
                Caso seja notado qualquer consulta ou a quebra do silêncio <br />
                O estudante está sujeito a ter sua prova zerada.
            </h5>
        </div>
        <hr />
        <div id="questoes">
            <ol>
                <li>(2,0)- Marque a alternativa <strong>CORRETA:</strong>
                    <p> a. Na div "headerProva" o espaço para nome do estudante é azul.</p>
                    <p> b. Não existe cor azul e zim violeta ou amarela.</p>
                    <p> c. Tudo é vermelho com exeção do local da nota.</p>
                    <p> d. Tudo é vermelho, inclusive a nota por que está dentro da da tag p.</p>
                    <p> e. Nenhuma das alternativas anteriores.</p>
                </li>
                <li>(2,0)- No arquivo css que temos nesse código de marcação:
                    <p> a. Temos um erro de edição de marcação, por tanto esse código é falho.</p>
                    <p> b. Temos o uso de uma pseudoclasse específica para apenas uma tag.</p>
                    <p> c. Temos o uso de uma classe para para toda tag html p.</p>
                    <p> d. Não tem classe sendo usada por que está incorreto a especificação.</p>
                    <p> e. Nenhuma das alternativas</p>
                    2
                </li>
                <li>(2,0) - DOM signfica___________________________________ e é uma _________.</li>
                <li>(2,0) - Assinale a alternativa <em>incorreta:</em>
                    <p class="questione">a. Neste ponto, toda o texto deste item é azul.</p>
                    <p> b. Aqui o texto é de cor padrão, ou seja, preto.</p>
                    <p> c. Caso não seja preto, obrigatoriamente é vermelho devido à tag p estilizada.</p>
                    <p> d. Apenas "a" e "b" são corretas.</p>
                    <p> e. Nenhuma das alternativas.</p>
                </li>
            </ol>
        </div>    
        <div id="ultimaQuestione">
            <ul>
                <li class="questione">5.(2,0) - Assinale a alternativa correta:</li>
                <li> a. Este item é totalmente vermelho por que faz parte também da classe criada.</li>
                <li> b. A única linha em vermelho é a div da questão por que foi estilizada.</li>
                <li> c. Todas os itens são vermelhos nessa questão.</li>
                <li> d. Apenas o primeiro item é vermelho e todos os outros são pretos(padrão).</li>
                <li> e. Nenhuma das alternativas.</li>
            </ul>
        </div>
    </div>
    </body>
</html>
```
