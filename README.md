# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. 
- Após a criação da conta escolhi o dataset que usarei nesse exemplo ("dataset-500-curso-sagemaker-canvas-dio")
- Salvei e criei com o nome Estoque

<img 
    src="./Imagens/02 dataset.png"
    width="300"
/>

### 2. 
-   O Dataset escolhido possui 4 anos, escolhi como target a coluna Quantidade_Estoque, o modelo de predição escolhido foi de 5 dias.
<img 
    src="./Imagens/03 target.png"
    width="300"
/>

### 3. 
-   Como podemos ver na imagem tem uma correlação do tipo matrix, onde consta as relações entre o ID_PRODUTO, FLAG_PROMOCAO e a QUANTIDADE_ESTOQUE

  <img 
    src="./Imagens/04 correlacao.png"
    width="300"
/>

### 4. 
-   Na imagem abaixo é possível ver o modelo escolhido:

<img 
    src="./Imagens/05 modelo.png"
   
/>

### 5.
- Não adicionei nenhuma transformação em relação a mudança da type, formula ou valores perdidos.

<img 
    src="./Imagens/06 analise.png"

/>

### 6.
- Escolhi o Target Quantidade_Estoque, pois o objetivo era analisar a quantidade de estoque com a data do evento e as vendas realizadas até o período.

<img 
    src="./Imagens/07 processo.png"
    width="300"
/>

### 7.
- Abaixo mostro os modelos de predição gerado

<img 
    src="./Imagens/08 canva.png"
   
/>

### 8. 
- Predição para o produto 4 com a flag de promoção 1

<img 
    src="./Imagens/09 predicao.png"
    
/>


## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
