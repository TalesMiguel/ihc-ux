O projeto irá consistir em cinco entregáveis: P1 ~ P5.
Cada pasta irá armazenar os respectivos produtos finais de cada parte do projeto.

[Link do High Fidelity Prototype no Figma](https://www.figma.com/design/ymdVMQNjssJiL8bwgfpeDr/P3?node-id=0-1&p=f&t=z34RowCjqeIiW9wh-0)

[Link das respostas da pesquisa de caso](https://docs.google.com/forms/u/1/d/1KkNClrla24x74o516I6zQJ9s83meB27efn6-pJLoMNY/edit?ts=67533b10#responses)
    [Sheets:](https://docs.google.com/spreadsheets/d/1ChPWc9CIPYNHgxIhL-9QI7xAS3Zpwmx0J3ccmgqcAyQ/edit?resourcekey=&gid=1433028335#gid=1433028335)

---

# **🍽️ Aplicativo de Receitas Limo**

## **Autores:**

* Laura Barbosa  
* Tales Miguel
* Walter Kenji  

## **📌 Sobre o Projeto**

Este projeto nasceu da ideia de desenvolver um aplicativo que sugere receitas com base em uma foto dos alimentos disponíveis na geladeira utilizando Inteligência Artificial. Além disso, incluímos algumas funcionalidades extras para melhorar a experiência do usuário:

* 📋 **Lista de compras**  
* ⏳ **Controle de validade dos alimentos**  
* 🔍 **Filtros de busca por tempo de preparo e dificuldade**

## **🎯 Pesquisa com o Público-Alvo**

Para validar nossa ideia, realizamos uma pesquisa por meio de um formulário online, direcionado a pessoas que:

* Não têm muito tempo para cozinhar  
* Precisam de mais criatividade para elaborar refeições

### **🔎 Resultados da Pesquisa**

A partir das respostas coletadas, destacamos os seguintes insights:

* 🍳 A maioria das pessoas cozinha algumas vezes por semana  
* 🍽️ Elas gostam de variar nos preparos das receitas  
* ⏰ A principal barreira para cozinhar mais é a falta de tempo e criatividade  
* 🛒 Muitas pessoas fazem listas de compras antes de ir ao mercado  
* ❄️ Alimentos costumam estragar com frequência na geladeira  
* 🔍 Buscam receitas novas, preferindo aquelas que utilizam ingredientes já disponíveis em casa

Com base nesse feedback, decidimos incluir no aplicativo a opção de inserir os ingredientes manualmente por meio de uma lista, além do reconhecimento via foto. 

![Gráfico de respostas do Formulários Google. Título da pergunta: Idade. Número de respostas: 32 respostas.](images/image1.png)

![Gráfico de respostas do Formulários Google. Título da pergunta: Sobre sua rotina, você:. Número de respostas: 32 respostas.][images/image2.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Caso trabalhe e/ou estude, isto é feito de que forma na maior parte do tempo?. Número de respostas: 32 respostas.][images/image3.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Com que frequência você costuma cozinhar?. Número de respostas: 32 respostas.][images/image4.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Quando cozinha, você costuma variar as receitas ou está limitado a um repertório reduzido?. Número de respostas: 32 respostas.][images/image5.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Se não está satisfeito, qual o principal motivo? (Escolha todas as opções que se aplicam). Número de respostas: 29 respostas.][images/image6.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Pensando em economia financeira e em melhoria dos seus hábitos alimentares, você gostaria de cozinhar com mais frequência?. Número de respostas: 32 respostas.][images/image7.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Você costuma fazer uma lista de compras antes de ir ao mercado?. Número de respostas: 32 respostas.][images/image8.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Você sente dificuldade em planejar uma lista de compras com base nos ingredientes que você irá utilizar ao longo do tempo?. Número de respostas: 32 respostas.][images/image9.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Com que frequência os alimentos estragam na sua geladeira/despensa. Número de respostas: 32 respostas.][images/image10.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Você costuma buscar novas receitas para cozinhar?. Número de respostas: 32 respostas.][images/image11.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Se sim, onde você busca novas receitas? (Selecione todas que se aplicam).. Número de respostas: 32 respostas.][images/image12.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Quando encontra alguma receita que te agrade, o que mais influencia na sua escolha? (Escolha até 2).. Número de respostas: 32 respostas.][images/image13.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Você já utilizou algum aplicativo ou site para buscar receitas?. Número de respostas: 32 respostas.][images/image14.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Se sim, o que você mais gostou na experiência?. Número de respostas: 32 respostas.][images/image15.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: O que você achou mais difícil ou frustrante ao utilizar um aplicativo/site de receitas?. Número de respostas: 32 respostas.][images/image16.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Se um aplicativo pudesse sugerir receitas baseadas nos ingredientes que você já tem em casa, você o utilizaria?. Número de respostas: 32 respostas.][images/image17.png]

![Gráfico de respostas do Formulários Google. Título da pergunta: Quais funcionalidades você acredita que seriam mais úteis num aplicativo de receitas? (Escolha até 3). Número de respostas: 32 respostas.][images/image18.png]

**📌 Desenvolvimento do Projeto**

### **📝 Planejamento**

1. **Flow Analysis e Sketches**

   * Criamos um **fluxo de navegação** para mapear a experiência do usuário dentro do app.  
     ![][images/image19.png]  
   * Desenvolvemos **sketches** para visualizar a interface e funcionalidades.  
     ![][images/image20.png]

     ![][images/image21.png]![][images/image22.png]![][images/image23.png]  
     ![][images/image24.png]  
2. **Protótipo de Baixa Fidelidade**

   * Elaboramos um primeiro rascunho para testar a usabilidade do app.  
     ![][images/image25.png]  
3. **Protótipo de Alta Fidelidade**

   * Criamos um protótipo interativo no Figma, representando o design final da aplicação.  
   * 🔗 [Acesse o protótipo no Figma](https://www.figma.com/design/ymdVMQNjssJiL8bwgfpeDr/P3?node-id=0-1&p=f&t=zZKnqbWPlVUK7Nbz-0)

## **🚀 Conclusão**

Nosso projeto busca facilitar o dia a dia das pessoas, reduzindo o desperdício de alimentos e tornando o preparo das refeições mais prático e acessível. O desenvolvimento do aplicativo passou por diversas etapas, desde a pesquisa com usuários até a prototipação no Figma, garantindo que as funcionalidades atendam às necessidades reais do público-alvo.

---
