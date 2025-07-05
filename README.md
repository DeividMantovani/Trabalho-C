
Este repositório contém um programa em C que adiciona, busca, filtra, atualiza e lista filmes.

Requisito: Possuir Clion instalado.

1. Faça o download do arquivo "ProgramaFilmes.zip"

2. Coloque-o na área de trabalho.

3. Clique com o botão direito sobre o arquivo e extraia.

4. Abra o Clion, nos 4 riscos no canto superior esquerdo procure por "Open".

5. Procure por "C:\Users\(Nome do usuário atual)\Desktop\ProgramaFilmes" e selecione o arquivo.

6. Espere carregar e rode o programa pressionando SHIFT + F10.



Como testar o código

Use o menu interativo
Ao executar, o terminal mostrará um menu como este:

1. Adicionar Filme
2. Buscar Filmes por Diretor
3. Filtrar Filmes por Gênero
4. Atualizar Avaliação de Filme
5. Listar Filmes
0. Sair
Digite o número da opção desejada e siga as instruções na tela.

🧭 Exemplos de uso
➕ Adicionar Filme (opção 1)
O sistema pedirá:

ID (número único)

Título

Diretor

Ano (ex: 1999)

Gênero (ex: ação, comédia...)

Avaliação (ex: 8.5)

✅ O sistema impede duplicações (mesmo título + diretor).

🔍 Buscar por Diretor (opção 2)
Digite parte do nome do diretor, como:

"Chris"

E o sistema exibirá todos os filmes dirigidos por ele.

🎭 Filtrar por Gênero (opção 3)
Digite o gênero exatamente como "ação", "drama", "comédia", etc.

O sistema não diferencia letras maiúsculas e minúsculas.

✏️ Atualizar Avaliação (opção 4)
Digite o ID do filme e depois a nova nota.

📋 Listar todos os filmes (opção 5)
Exibe todos os filmes ordenados por:

Ano de lançamento (do mais antigo ao mais recente)

Título (ordem alfabética, caso os anos sejam iguais)

❌ Sair (opção 0)
Salva automaticamente os dados no arquivo filmes.csv

Libera a memória usada

🗃️ Observação
Os dados ficam armazenados no arquivo filmes.csv, que é lido e atualizado automaticamente sempre que o programa é executado.

Se o arquivo não existir, ele será criado ao adicionar o primeiro filme.

💡 Dica
Se quiser apagar todos os filmes cadastrados, você pode excluir manualmente o arquivo filmes.csv e rodar o programa novamente.


