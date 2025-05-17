# Projetos Alura

# Projeto 1 : LookIA

# Análise de Looks de Roupa com Gemini Pro Vision no Google Colab

Este projeto demonstra como utilizar o modelo Gemini do Google AI para analisar imagens de looks de roupa. Através de dois agentes distintos, a IA é capaz de identificar as peças presentes, descrever suas características, sugerir a ocasião mais adequada para o look e propor possíveis combinações com outras peças.

## Visão Geral

O projeto consiste em um script Python executável no Google Colaboratory que realiza os seguintes passos:

1.  **Upload de Imagens:** Permite ao usuário carregar múltiplas imagens de looks de roupa diretamente no ambiente Colab.
2.  **Carregamento e Preparação:** As imagens carregadas são processadas para serem utilizadas pelo modelo Gemini.
3.  **Análise por Agentes:**
    * **Agente de Identificação de Peças e Características:** Analisa a imagem para identificar cada peça de roupa, descreve suas cores, tecidos, modelagens e outros detalhes, e sugere um nome para cada peça.
    * **Agente de Análise de Ocasião e Combinações:** Utiliza a análise do primeiro agente para determinar a ocasião mais apropriada para o look e sugere combinações adicionais de peças que complementariam o visual.
4.  **Apresentação dos Resultados:** Os resultados da análise de cada agente para cada imagem são exibidos de forma clara no Colab.

## Como Utilizar

1.  **Pré-requisitos:**
    * Uma conta Google.
    * Acesso ao Google Colaboratory (colab.research.google.com).
    * Uma chave de API do Google AI Studio. Você pode obter uma gratuitamente em [Google AI Studio](https://makersuite.google.com/app/apikey).

2.  **Configuração:**
    * Abra um novo notebook no Google Colab.
    * Cole o código Python fornecido nas células do notebook.
    * Na célula onde a variável `GOOGLE_API_KEY` está definida, substitua `"SUA_CHAVE_AQUI"` pela sua chave de API do Google AI Studio.

3.  **Execução:**
    * Execute as células do notebook em sequência.
    * Quando a célula com a função `upload_imagens()` for executada, um botão "Choose Files" aparecerá. Clique nele e selecione as imagens dos looks de roupa que você deseja analisar. Você pode selecionar múltiplas imagens.
    * Após o upload das imagens, as células subsequentes executarão a análise de cada imagem pelos agentes Gemini Pro Vision.
    * Os resultados da análise (identificação de peças, características, ocasião sugerida e combinações) serão impressos na saída do notebook para cada imagem.

## Estrutura do Código

O código principal é composto pelas seguintes funções:

* `upload_imagens()`: Permite o upload de múltiplas imagens pelo usuário no Colab.
* `carregar_e_preparar_imagem(nome_arquivo, dados_arquivo)`: Carrega uma imagem a partir dos dados do arquivo e a prepara para o Gemini.
* `analisar_pecas_e_caracteristicas(imagem)`: O primeiro agente, responsável por identificar e descrever as peças de roupa.
* `analisar_ocasiao_e_combinacoes(analise_pecas, imagem)`: O segundo agente, que analisa a ocasião e sugere combinações com base na análise das peças.
* O bloco principal do código que orquestra o upload, o processamento e a análise de cada imagem.

## Possíveis Melhorias e Expansões

Este projeto pode ser expandido de diversas maneiras, incluindo:

* **Mais Agentes:** Adicionar agentes com focos específicos, como análise de cores, estilo pessoal, adequação a diferentes tipos de corpo, etc.
* **Refinamento dos Prompts:** Ajustar os prompts dos agentes para obter resultados mais detalhados e precisos.
* **Interface de Usuário:** Criar uma interface gráfica mais amigável para o upload e visualização dos resultados, utilizando bibliotecas como Gradio ou Streamlit.
* **Salvamento dos Resultados:** Implementar a funcionalidade de salvar os resultados da análise em um arquivo (por exemplo, CSV ou JSON).
* **Análise em Tempo Real:** Se integrado com uma câmera, permitir a análise de looks em tempo real.

## Contribuição

Contribuições para este projeto são bem-vindas! Se você tiver ideias de melhorias, novos agentes ou correções de bugs, sinta-se à vontade para abrir uma issue ou enviar um pull request.






##################################################################################################################################################

#Projeto 2
Meu Estilo AI
Funcionalidades Atuais (Demonstração):

    Upload de Fotos: Uma interface web simples (construída com Gradio) permite que os usuários tirem fotos ou carreguem imagens de suas roupas.
    Adição ao Guarda-Roupa Virtual: Ao adicionar uma foto, a aplicação simula o armazenamento da peça no guarda-roupa virtual do usuário, exibindo uma mensagem de confirmação.
    Visualização Recente: Uma galeria exibe as últimas fotos de roupas adicionadas, oferecendo uma representação visual do guarda-roupa em tempo real (limitado às últimas 5 adições e não persistente entre sessões).

Funcionalidades Futuras (Planejadas):

    Análise Inteligente de Roupas: Utilizar a API Gemini Vision para identificar automaticamente o tipo de peça de roupa, suas cores, estampas e outras características relevantes.
    Categorização Automática: Organizar as roupas do guarda-roupa virtual em categorias como "Superiores", "Inferiores", "Calçados" e "Acessórios".
    Sugestão de Looks: A IA analisará as peças no guarda-roupa e proporá combinações de looks com base no estilo do usuário, ocasião e preferências.
    Busca por Peças Similares: Integrar a capacidade de buscar por roupas semelhantes em plataformas de e-commerce, como a Shein, a partir de fotos do guarda-roupa virtual ou de outras imagens.
    Sistema de Login e Senha: Implementar autenticação de usuários para que cada pessoa tenha seu próprio guarda-roupa virtual privado e persistente.
    Persistência de Dados: Armazenar as informações do guarda-roupa virtual (fotos e metadados) em um banco de dados para que os dados sejam mantidos entre as sessões.

Tecnologias Utilizadas (Demonstração):

    Python: Linguagem de programação principal.
    Google Cloud AI (Gemini API): Para a futura análise de imagens e sugestão de looks.
    Gradio: Biblioteca Python para criar rapidamente a interface web interativa para demonstração.
    PIL (Pillow): Biblioteca para manipulação de imagens.
    io e base64: Para manipulação de dados de imagem (tentativas de visualização).
    tempfile e os: Para manipulação de arquivos temporários (tentativas de visualização).

Status do Projeto:

Este projeto está atualmente em fase de demonstração da interface de upload e visualização básica. As funcionalidades de análise inteligente, sugestão de looks e persistência de dados são planejadas para desenvolvimentos futuros.

Como Executar (Demonstração com Google Colab):

    Abra o notebook do Google Colab (.ipynb fornecido, se aplicável).
    Certifique-se de ter uma chave de API do Google Cloud configurada corretamente (substitua "SUA_CHAVE_DE_API_NOVA" pela sua chave).
    Execute as células de código em sequência.
    O link público do Gradio será exibido. Clique no link para interagir com a interface web no seu navegador.

Observações:

    A funcionalidade de visualização das miniaturas das fotos pode ter limitações na demonstração atual devido a questões de compatibilidade com o Gradio no ambiente do Colab. O status de "Adicionado!" confirma o envio da imagem.
    As funcionalidades de análise de IA e sugestão de looks ainda não estão implementadas e serão o foco de desenvolvimentos futuros.

Contribuição:

Contribuições para o desenvolvimento futuro deste projeto são bem-vindas!
