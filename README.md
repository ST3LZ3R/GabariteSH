## GabariteSH
Projeto responsável por requisitar api do site gabarite e obter a questão correta através do id da questão e uma alternativa qualquer.  
Site: https://www.gabarite.com.br  
Doações: PIX para maiconstelzer@pm.me (Banco Caixa Econômica Federal)

#### Bibliotecas necessárias
---
> Bash
> Curl

#### Utilização
---
> 1. Clonar o repositório  
> 1. Dar permissão de execução de script (chmod +x) para o arquivo `gabarite.sh`  
> 1. Executar o arquivo seguindo a ordem dos parâmetros:  
>    `./gabarite.sh IdQuestao AlternativaQualquer`
> 1. No corpo de retorno sera apresentada a resposta verdadeira

#### Observações
---  
> 1. IdQuestao é o código ID da questão, normalmente no começo da questão, exemplo: 208935 é o id dessa https://www.gabarite.com.br/questoes-de-concursos/208935-questao)    
> 1. AlternativaQualquer é uma alternativa qualquer em minúsculo, exemplo: d  
> 1. Video tutorial de uso:  
> ![Tutorial](./media/tutorial.mp4)
