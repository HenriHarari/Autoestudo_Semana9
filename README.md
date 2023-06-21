# Autoestudo_Semana9
Atuestudo Henri Harari - semana 9
# Ferramentas de NLP na Nuvem Comercial
A seguir, apresento uma lista de serviços de Processamento de Linguagem Natural (NLP) disponíveis em uma nuvem comercial, juntamente com um exemplo de aplicação de cada um deles. É importante ressaltar que essa lista é uma amostra e pode não incluir todos os serviços disponíveis. Além disso, optei por dar preferência a implementações baseadas em requisições HTTP em vez de bibliotecas específicas do fabricante, sempre que possível.


##  Microsoft Azure Text Analytics
### Descrição: O Microsoft Azure Text Analytics é um serviço de NLP que oferece recursos para análise de sentimentos, extração de entidades, detecção de idioma e muito mais. Ele pode ser integrado facilmente a aplicativos por meio de uma API RESTful.

### Exemplo de Aplicação: Um exemplo de aplicação seria a detecção de idioma em um conjunto de tweets. O serviço poderia ser utilizado para identificar automaticamente o idioma de cada tweet, permitindo que as empresas analisem o sentimento expresso em diferentes idiomas nas redes sociais.

### Exemplo de requisição HTTP utilizando cURL:

```curl -X POST -H "Content-Type: application/json" \```

     ``` -H "Ocp-Apim-Subscription-Key: API_KEY" \```
     
     ``` -d '{"documents":[{"id":"1","text":"This is a``` 

 O Microsoft Azure Text Analytics é um serviço de processamento de linguagem natural (NLP) que oferece diversos recursos para análise de texto. Abaixo, vou fornecer exemplos de aplicação para cada um desses recursos:

### Detecção de Idioma:
O Text Analytics pode identificar automaticamente o idioma em que um texto está escrito. Isso é útil para categorizar e processar corretamente documentos multilíngues.

### Análise de Sentimento: 
O serviço pode analisar o sentimento expresso em um texto, identificando se o conteúdo é positivo, negativo ou neutro. Isso pode ser aplicado em análises de feedback de clientes, avaliações de produtos, mídias sociais, entre outros.

### Extração de Frases-Chave:
O Text Analytics pode identificar as frases mais importantes e significativas em um texto. Isso ajuda a extrair informações-chave e resumir o conteúdo de um documento.

### Extração de Entidades:
O serviço é capaz de extrair entidades nomeadas, como nomes de pessoas, locais, organizações, datas, valores monetários, por exemplo. Isso é útil para identificar informações específicas em documentos e auxiliar na classificação e organização dos mesmos.

### Reconhecimento de Entidades com Vínculo:
O Text Analytics pode reconhecer entidades em um texto e, além disso, identificar os relacionamentos entre essas entidades. Por exemplo, se o texto menciona uma pessoa e uma organização, o serviço pode indicar que a pessoa é afiliada à organização.

### Detecção de Tópicos:
O serviço pode identificar os tópicos principais abordados em um conjunto de documentos. Isso é útil para organizar grandes volumes de informações, classificar documentos ou encontrar tendências em um conjunto de textos.

### Análise de Opinião: 
O Text Analytics pode analisar as opiniões expressas em um texto, identificando se elas são positivas, negativas ou neutras. Isso é útil para a análise de sentimentos em avaliações de produtos, feedback de clientes, pesquisas de satisfação, entre outros.

Esses são apenas alguns exemplos de aplicação do Microsoft Azure Text Analytics. O serviço oferece recursos poderosos para processamento de linguagem natural que podem ser integrados a aplicativos por meio de sua API RESTful.
