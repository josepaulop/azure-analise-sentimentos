# azure-analise-sentimentos
Análise de sentimentos por IA utilizando o Azure - Language Studio


# Criar um recurso Azure Language Service
1. Acessar https://azure.microsoft.com/pt-br/products/ai-services e criar sua conta gratuitamente utilizando o recurso de sua universidade ou empresa.

![image](https://github.com/user-attachments/assets/2f446bc7-6dcb-4e21-8b53-01a58722f5ca)

2. Após criar a conta, vá em Mais serviços.

![image](https://github.com/user-attachments/assets/80fb2767-45ca-4064-8709-f5020d4285da)

3. Selecione em categorias "IA + MACHINE LEARNING" e depois de selecionar essa categoria, selecione "Language"

![image](https://github.com/user-attachments/assets/97b90fa8-6563-477b-9698-03f866d5a202)

4. Caso você não tenha nenhuma linguagem de serviço criada, vá em Criar e siga as etapas de criação de serviço.

![image](https://github.com/user-attachments/assets/3d34ab6f-5926-426b-96b8-71ef38a78ac3)

5. Após criar o serviço de linguagem, vá no seu serviço criado e vá em "Language Studio" e selecione "Get started with Language Studio"

![image](https://github.com/user-attachments/assets/e1c9e749-9697-4aeb-a63a-571c4e11ca9d)

6. Vá em "Classify text" e selecione "Analyze sentiment and mine opinions" em Try it out

![image](https://github.com/user-attachments/assets/f85adfbf-1c22-4207-a89c-0d0da5ce51b6)

7. Coloque a linguagem de texto em "Portuguese (Brasil)" e faça o upload do seu arquivo de teste.txt para a plataforma (fica a seu critério utilizar Enable opinion ming)

![image](https://github.com/user-attachments/assets/d2cd2a91-636c-436a-85c2-bbbc2cd6d503)
![image](https://github.com/user-attachments/assets/17cd8685-cb9e-46fb-a370-3e8b903a7051)


# Resultados
Abaixo podemos ver o resultado da análise de sentimento de todo o texto. De acordo com os resultados, o texto é majotariamente negativo com 81% e possui um intervalo de confiança de apenas 15%.

![image](https://github.com/user-attachments/assets/50c63752-80c2-42b3-ac62-a5e31a054cf1)

Algumas sentenças tiveram resultados negativos, outros neutros e poucos positivos. Segue abaixo alguns exemplos de sentenças:

![image](https://github.com/user-attachments/assets/8c2d5b2b-798a-4028-91c7-5d1ae9f71262)

![image](https://github.com/user-attachments/assets/c5541b8b-0686-4adc-bf40-e49d3cf31598)


# Conclusão
Ferramentas de análise de sentimentos e opiniões desempenham um papel importante na automação da avaliação de feedbacks sobre serviços. Embora sejam altamente eficazes na análise de textos que expressam sentimentos de forma explícita, como avaliações de produtos e comentários diretos, essas ferramentas demonstram certas limitações quando aplicadas a textos em que as emoções não estão tão claramente delineadas. Isso possivelmente ocorre porque a análise é conduzida sentença por sentença, sem considerar o contexto completo do conteúdo. Uma abordagem tecnológica que conectasse diferentes sentenças e interpretasse o texto como um todo poderia alcançar resultados mais precisos e abrangentes.


   
