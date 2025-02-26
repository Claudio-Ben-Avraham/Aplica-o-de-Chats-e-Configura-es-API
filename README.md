Aplicação de Chats e Configurações API

Este repositório contém uma aplicação prática que explora o desenvolvimento de chats interativos utilizando Azure OpenAI e integrações com o Semantic Kernel. O objetivo deste projeto é demonstrar como é possível criar um sistema de chat inteligente, configurando a API e integrando com o Semantic Kernel para melhorar a experiência do usuário.
Objetivo

O principal objetivo deste projeto é explorar a integração do Azure OpenAI com APIs para criar uma aplicação de chat funcional. Ao longo do desenvolvimento, abordaremos tópicos como:

    Chamadas de API para se conectar com o Azure OpenAI.
    Integração com o Semantic Kernel para processar a linguagem de maneira mais eficiente.
    Como configurar e personalizar a API do Azure para otimizar as interações.

Este repositório contém o código-fonte da aplicação, juntamente com instruções para implementação e integração.
Funcionalidades

    Conexão com o Azure OpenAI API para gerar respostas de linguagem natural.
    Integração com o Semantic Kernel para melhorar o processamento e compreensão da linguagem.
    Interface de Chat que permite interagir com o modelo de IA em tempo real.
    Personalização e configuração da API para melhorar a acurácia e a relevância das respostas.

Como Executar
Pré-requisitos

Antes de começar, é necessário garantir que você tenha os seguintes requisitos instalados:

    Python 3.8+
    Azure OpenAI API Key – você pode obter sua chave acessando o portal do Azure OpenAI.
    Semantic Kernel SDK – necessário para a integração com o kernel semântico.

Instalação

    Clone o repositório:

git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
cd NOME_DO_REPOSITORIO

Crie e ative um ambiente virtual:

python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate  # Para Windows

Instale as dependências:

pip install -r requirements.txt

Configure as variáveis de ambiente com sua chave da Azure OpenAI:

No terminal ou em um arquivo .env:

    AZURE_API_KEY="SUA_CHAVE_API"

Rodando a aplicação

Após configurar tudo, você pode rodar a aplicação de chat:

python app.py

O chat será iniciado e você poderá começar a interagir com o modelo de IA.
Estrutura do Projeto

    app.py: Arquivo principal onde a aplicação de chat é inicializada e gerencia as interações.
    config.py: Arquivo de configuração para armazenar variáveis de ambiente e chaves da API.
    semantic_kernel.py: Implementação da integração com o Semantic Kernel para processar a linguagem.
    requirements.txt: Lista de dependências necessárias para a execução do projeto.
