Reconhecimento de Celebridades com Amazon Rekognition

  **Descrição do Projeto**

  Este projeto utiliza o Amazon Rekognition, um serviço de aprendizado profundo da AWS, para identificar celebridades em imagens. A aplicação processa imagens fornecidas, detecta rostos de celebridades conhecidas, e marca os rostos detectados com caixas delimitadoras e nomes.

   **Funcionalidades**

  Reconhecimento Automático: Identificação de celebridades em imagens.
  
  Marcação Visual: Adição de caixas delimitadoras ao redor dos rostos detectados e anotação com os nomes das celebridades.
  
  Configuração Personalizável: Fácil troca de imagens e fontes.

  **Tecnologias Utilizadas**

  Python: Linguagem principal do projeto.
  
  Amazon Rekognition: Serviço de aprendizado profundo para reconhecimento de celebridades.
  
  Pillow (PIL): Biblioteca Python para manipulação de imagens.
  
  Boto3: Biblioteca AWS SDK para Python, usada para comunicação com o Rekognition.

**Como Funciona**

  Carregamento da Imagem: A imagem é carregada do diretório images.
  
  Envio para o Rekognition: A imagem é processada pelo serviço Amazon Rekognition para identificar celebridades.
  
  Processamento de Resultados:
  
  Rostos detectados são destacados com caixas delimitadoras.
  Nomes das celebridades são adicionados próximos às caixas.
  
  Saída Final: A imagem processada é salva no mesmo diretório com o nome original do arquivo.

**Possibilidades e Expansões**

Análise de Grupos: Processar imagens com múltiplas celebridades.

Relatórios Detalhados: Gerar relatórios em JSON com informações sobre as celebridades detectadas.

Aplicações Reais: Identificação automática de celebridades para uso em eventos, redes sociais ou marketing.
