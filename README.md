# Automação de Cadastro de Produtos com Python 🛒✨

Este projeto demonstra como automatizar o cadastro de produtos em um sistema web usando Python e a biblioteca PyAutoGUI. A automação lê dados de um arquivo CSV e os insere em formulários web, simulando as ações de um usuário (cliques, digitação e pressionamento de teclas).

## Funcionalidades

Login automático: 
🔑 O script acessa uma URL de login, preenche os campos de e-mail e senha e faz o login.

Leitura de dados: 
📄 Utiliza a biblioteca Pandas para ler e processar os dados de produtos de um arquivo produtos.csv.

Preenchimento de formulário: 
✍️ Navega pelos campos do formulário de cadastro de produtos e preenche cada um com os dados correspondentes do arquivo CSV.

Cadastramento em lote: 
🚀 Itera sobre todas as linhas do arquivo CSV para cadastrar múltiplos produtos de forma sequencial.

## Estrutura do projeto

gabarito.py: 
🐍 O script principal que contém o código de automação.

produtos.csv: 
📊 A planilha com os dados dos produtos a serem cadastrados.

pegar_posicao.py: 
📍 Um script auxiliar para identificar as coordenadas de cliques na tela (útil para adaptar o código a diferentes resoluções de tela).

## Requisitos

Certifique-se de ter as seguintes bibliotecas instaladas:

pyautogui

pandas

Você pode instalá-las usando o pip:

pip install pyautogui pandas

### Como usar

⚙️ Clone este repositório para a sua máquina local.

📂 Certifique-se de que os arquivos gabarito.py, produtos.csv e pegar_posicao.py estejam no mesmo diretório.

🎯 Adapte as coordenadas de clique no arquivo gabarito.py se a sua tela tiver uma resolução diferente da usada no desenvolvimento do script (as coordenadas atuais estão otimizadas para a resolução de 1920x1080). Se precisar encontrar as coordenadas corretas para sua tela, execute o arquivo pegar_posicao.py e clique nos locais desejados para obter as coordenadas.

🔒 Substitua "sua senha" pela senha de login no arquivo gabarito.py.

➡️ Execute o script gabarito.py para iniciar a automação.

python gabarito.py

### Observação

⚠️ O script foi desenvolvido para a URL https://dlp.hashtagtreinamentos.com/python/intensivao/login. Se o formulário ou a página mudarem, as coordenadas de clique e os comandos de navegação precisarão ser atualizados.
