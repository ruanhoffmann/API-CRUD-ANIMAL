# API-CRUD-ANIMAL

BAIXANDO O ARQUIVO API:

1º Passo: Faça o download do arquivo no Github.

2º Passo: Passe para a pasta de Documentos e extraia o ZIP na pasta.

__________________________________________________________________________________________________________

ABRINDO O ARQUIVO NO INTELLIJ:

1º Passo:  Abra seu Intellij e clique no canto superior esquerdo "File", em seguida clique em "Open".

2º Passo: Vá para a pasta Documentos e encontre a pasta api e clique nela para selecionar, em sequida clique em OK.
__________________________________________________________________________________________________________

TESTANDO A API

1º Passo: Com o projeto aberto, clique em src -> java -> com.example.APICrudAnimais.api -> controller -> AnimaisController.
2º Passo: Abra ApiApplication em com.example.APICrudAnimais.api, e depois clique em Run(canto superior direito).
3º Passo: O Intellij vai começar a contruir a API no seu PC, e em sequida o TOMCAT vai startar o server na porta 8080.
4º Passo: Abra o PostMan no Google Chrome, e em Collections mesmo, clique em body, depois  raw, depois em Text e altere para JSON.
5º Passo: Selecione POST e insira essa URL http://localhost:8080/animal
6º Passo: Copie e cole essa linha de código: 
{
    "descricaoAnimal": "Cachorro"
    
}

7º Passo: Clique em Send.
8º Passo: Após ir inserindo os animais, troque de POST para GET, e ai você vai puxar os animais que acabou de adicionar.
