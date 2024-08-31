# Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Passo a passo do projeto Reconhecimento Facial e Transformação de imagens em Dados no Azure ML da DIO.

## 1 - Criando recurso e detectando rosto

Abrindo o portal Azure. Cliquei em "Create a resourse" na imagem.

![Img](inputs/01.png)

Em "categorias". Cliquei na opção "IA + Machine Learning"

![Img](inputs/02.png)

Pesquisei por "Azure AI services". Cliquei em "create, seguindo a documentação proposta".

![Img](inputs/03.png)

Ao criar abrir o Vision Studio ([azure.com](https://portal.vision.cognitive.azure.com/gallery/featured))

![Img](inputs/04.png)

Alterando o tema para o modo "Dark". Cliquei em "View All Resources" e selecionado o recurso criado "LabRF-TI" (Referênte ao nome do curso "Reconhecimento Facial e transformação de imagens em Dados no Azure ML").

![image](inputs/05.png)

Ao clicar no "X" foi retornado para a página inicial e selecionada a opção "Face".

![image](inputs/06.png)

Cliquei em "Detect Faces In na Image" e selecionado o "Try It Out"

![image](inputs/07.png)

A imagem e o rosto da pessoa foi detectado com o atributo e o código em JSON

![image](inputs/08.png)

[Clique aqui para ver o código](output/DetectandoRosto.json)

## 2 - Análise de documentos

Retornei a página inicial e selecionada a opção em "Optical Character Recognition" para fazer análise de caracteres e abrir o "Extract text from images".

![image](inputs/09.png)

![image](inputs/10.png)

![image](inputs/11.png)

[Clique aqui para ver o código](output/AnaliseDeDocumentos.json)

![image](inputs/12.png)

## 3 - Análise de imagem
Retornado novamente, cliquei em "Image Analysis"

![image](inputs/13.png)

E escolhi a opção "Add Dense Captions To Images". Selecionando uma imagem, ele traz toda a descrição em atributos e o código JSON e a descrição serve também como acessibilidade.

![image](inputs/14.png)

![image](inputs/15.png)

[Clique aqui para ver o código](output/AnaliseDeImagem.json)

![image](inputs/16.png)
