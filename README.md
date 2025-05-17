# Meu Estilo IA

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
