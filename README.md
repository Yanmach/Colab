
👗 Projeto 1: LookIA - Seu Consultor de Moda com IA 🤖

  Análise Inteligente de Looks com Gemini Pro Vision no Google Colab




🔗 **Link do vídeo explicando a visão e ideia do projeto:** [https://drive.google.com/file/d/1wwH8Jyk7DuRQ8vFr8GTBUFgiu9qtrc-7/view?usp=sharing](https://drive.google.com/file/d/1wwH8Jyk7DuRQ8vFr8GTBUFgiu9qtrc-7/view?usp=sharing)



## ✨ Visão Geral

O **LookIA** é um projeto fascinante que utiliza o poder do modelo **Gemini Pro Vision** do Google AI para analisar imagens de looks de roupa. Através de dois agentes inteligentes, a IA é capaz de:

* 🔍 **Identificar as peças** presentes na imagem.
* 🎨 **Descrever suas características**, como cor, tecido e modelagem.
* 📅 **Sugerir a ocasião mais adequada** para o look.
* 💡 **Propor possíveis combinações** com outras peças.

Este projeto é um script Python executável no ambiente **Google Colaboratory**.

## ⚙️ Como Funciona

O script segue os seguintes passos para analisar seus looks:

1.  📤 **Upload de Imagens:** Você carrega múltiplas fotos de looks diretamente no Colab.
2.  🖼️ **Carregamento e Preparação:** As imagens são processadas para serem compatíveis com o modelo Gemini.
3.  🧠 **Análise por Agentes de IA:**
    * **🕵️‍♂️ Agente de Identificação:** Examina a imagem, reconhece as peças e detalha suas propriedades.
    * **👔 Agente de Estilo:** Interpreta a análise do primeiro agente para sugerir a melhor ocasião e combinações criativas.
4.  📊 **Apresentação dos Resultados:** As análises de cada agente são exibidas de forma clara no Colab.

## 🚀 Primeiros Passos

Para experimentar o LookIA, siga estas instruções:

1.  🔑 **Pré-requisitos:**
    * ✅ Uma conta Google ativa.
    * 💻 Acesso ao [Google Colaboratory](https://colab.research.google.com).
    * 🔑 Uma chave de API do [Google AI Studio](https://makersuite.google.com/app/apikey) (você pode obter uma gratuitamente!).

2.  🛠️ **Configuração:**
    * Abrir um novo notebook no [Google Colab](https://colab.research.google.com).
    * Copiar e colar o código Python fornecido nas células do notebook.
    * ✏️ Na célula onde a variável `GOOGLE_API_KEY` está definida, substitua `"SUA_CHAVE_AQUI"` pela sua chave de API do Google AI Studio.

3.  ▶️ **Execução:**
    * Executar as células de código sequencialmente.
    * Quando a célula de upload (`upload_imagens()`) for executada, um botão "Choose Files" aparecerá. Clique para selecionar as fotos dos seus looks. Você pode selecionar várias imagens!
    * Após o upload, as células seguintes realizarão a análise com os agentes Gemini Pro Vision.
    * Os resultados da análise (peças, características, ocasião e combinações) serão mostrados na saída do Colab.

## 🧱 Estrutura do Código

O código principal é organizado nas seguintes funções:

* `upload_imagens()`: Permite o fácil upload de múltiplas imagens no Colab.
* `carregar_e_preparar_imagem(nome_arquivo, dados_arquivo)`: Carrega e otimiza uma imagem para o Gemini.
* `analisar_pecas_e_caracteristicas(imagem)`: O agente de IA que identifica e descreve as roupas.
* `analisar_ocasiao_e_combinacoes(analise_pecas, imagem)`: O agente de IA que sugere ocasiões e combinações.
* O bloco principal que coordena o fluxo de upload, processamento e análise.

## 🔮 Próximos Passos e Ideias

O LookIA tem um futuro promissor com diversas possibilidades de expansão:

* ➕ **Mais Agentes:** Integrar agentes para análise de cores, estilo pessoal e adequação ao tipo de corpo.
* ✨ **Prompts Aprimorados:** Refinar as instruções para os agentes para obter análises ainda mais precisas e detalhadas.
* 🎨 **Interface de Usuário:** Desenvolver uma interface web intuitiva com bibliotecas como Gradio ou Streamlit para facilitar o uso.
* 💾 **Salvamento de Resultados:** Implementar a opção de salvar as análises em formatos como CSV ou JSON.
* 🎥 **Análise em Tempo Real:** Integrar com câmeras para análise de looks em tempo real.

## 🤝 Contribuição

Sinta-se à vontade para contribuir com o desenvolvimento do LookIA! Ideias de melhorias, novos agentes e correções de bugs são sempre bem-vindos. Abra uma issue ou envie um pull request!

---

👚 Projeto 2: Meu Estilo AI - Seu Guarda-Roupa Inteligente 🧠</h1>

<br>

## ✨ Funcionalidades Atuais (Demonstração)

O **Meu Estilo AI** é uma demonstração de um futuro guarda-roupa virtual inteligente:

* 📸 **Upload de Fotos:** Uma interface web simples (com **Gradio**) para tirar fotos ou carregar imagens de suas roupas.
* ➕ **Adição ao Guarda-Roupa Virtual:** Simulação de adicionar a peça ao seu guarda-roupa virtual com uma mensagem de confirmação.
* 🖼️ **Visualização Recente:** Uma galeria das últimas 5 adições ao seu guarda-roupa (não persistente entre sessões).

## 🔮 Funcionalidades Futuras (Planejadas)

O futuro do Meu Estilo AI inclui:

* 👓 **Análise Inteligente de Roupas (Gemini Vision):** Identificação automática de tipo, cor, estampa e características das peças.
* 📂 **Categorização Automática:** Organização inteligente do guarda-roupa (Superiores, Inferiores, Calçados, Acessórios).
* 👗 **Sugestão de Looks:** Recomendações de combinações baseadas no seu estilo, ocasião e preferências (com IA).
* 🛍️ **Busca por Peças Similares (Shein):** Encontrar roupas semelhantes em plataformas de e-commerce a partir de fotos.
* 🔒 **Sistema de Login e Senha:** Guarda-roupa virtual privado e seguro para cada usuário.
* 💾 **Persistência de Dados:** Armazenamento das informações do guarda-roupa em um banco de dados.

## 🛠️ Tecnologias Utilizadas (Demonstração)

* 🐍 **Python:** A linguagem principal.
* ☁️ **Google Cloud AI (Gemini API):** Para análise de imagens e sugestão de looks (futuro).
* 🖼️ **Gradio:** Para criar a interface web de demonstração.
* <0xF0><0x9F><0x8E><0x9E> **PIL (Pillow):** Para manipulação de imagens.
* 📦 **io e base64:** Para lidar com dados de imagem.
* ⏳ **tempfile e os:** Para manipulação de arquivos temporários.

## 🚦 Status do Projeto

Atualmente em fase de **demonstração da interface básica de upload e visualização**. As funcionalidades de IA e persistência de dados estão planejadas para o futuro.

## ▶️ Como Executar (Demonstração com Google Colab)

1.  📂 Abra o notebook do Google Colab (.ipynb fornecido).
2.  🔑 Certifique-se de ter sua chave de API do Google Cloud configurada (substitua `"SUA_CHAVE_DE_API_NOVA"` pela sua).
3.  🚀 Execute as células de código em sequência.
4.  🔗 Um link público do Gradio será exibido. Clique para interagir com a interface web no seu navegador!

⚠️ **Observações:** A visualização de miniaturas pode ter limitações no Colab. O status "Adicionado!" confirma o envio da imagem. As funcionalidades de IA ainda não estão implementadas.

## 🤝 Contribuição

Contribuições para o desenvolvimento futuro do Meu Estilo AI são muito bem-vindas!
```
