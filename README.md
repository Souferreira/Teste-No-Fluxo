
# Descubra seu Estágio no Fluxo

Este é um projeto interativo em **HTML**, **CSS** e **JavaScript** que permite ao usuário identificar o estágio em que está em sua jornada rumo ao estado de fluxo ideal. Ao selecionar um estágio, você receberá uma explicação sobre sua situação atual e dicas para avançar para o próximo nível.

## 🔍 Sobre o Projeto

A ideia central do projeto é ajudar as pessoas a se identificarem em uma das fases de progresso pessoal ou profissional, com base em como se sentem atualmente em relação às suas tarefas, foco e produtividade. O objetivo é orientar o usuário a entender seu estado e fornecer dicas para alcançar um estado de alto desempenho e fluxo constante.

O projeto utiliza HTML, CSS e JavaScript puro, sendo ideal para iniciantes explorarem conceitos básicos de design responsivo, manipulação DOM e lógica interativa.

---

## 🎯 Funcionalidades

- **Seleção Interativa de Estágios**: O usuário escolhe entre diferentes estágios, que representam estados emocionais e mentais comuns.
- **Resultados Personalizados**: Após a seleção, é exibida uma descrição detalhada do estágio escolhido, incluindo sugestões de melhoria.
- **Design Responsivo e Minimalista**: Interface amigável, funcional e compatível com diferentes tamanhos de tela.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Para a estruturação do conteúdo.
- **CSS3**: Para o design e estilização.
- **JavaScript**: Para a lógica interativa e manipulação dos elementos DOM.

---

## 📂 Estrutura de Arquivos

```plaintext
DescubraSeuEstagioNoFluxo
├── index.html   # Arquivo principal com o conteúdo e a estrutura HTML
├── style.css    # Estilos gerais aplicados ao projeto
└── script.js    # Lógica interativa do projeto
```

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/Souferreira/Teste-No-Fluxo.git
   ```

2. **Navegue até o diretório do projeto:**

   ```bash
   cd DescubraSeuEstagioNoFluxo
   ```

3. **Abra o arquivo HTML no navegador de sua preferência:**

   ```bash
   indexatualizado.html
   ```

---

## 📖 Estágios Explicados

1. **Sonolência**

   - Você se sente desmotivado e sem energia, como se estivesse em um estado de sonolência. Há dificuldade em dar o primeiro passo para mudanças.

2. **Despertar**

   - Uma insatisfação inicial surge, acompanhada de um desejo de mudança, mas ainda sem saber por onde começar.

3. **Sobrecarga de Informação**

   - Muitas informações foram absorvidas, mas a quantidade parece esmagadora, gerando confusão sobre como agir.

4. **Execução sem Estratégia**

   - Há ação, mas sem planejamento, levando a frustrações ou pausas frequentes no processo.

5. **Organização e Planejamento**

   - O foco passa a ser organizar e planejar de forma eficiente, buscando melhorar o uso do tempo e dos recursos.

6. **Execução Fluida**

   - Você começa a executar as tarefas com fluidez e naturalidade, alcançando melhorias constantes.

7. **Fluxo Constante**

   - O ápice da jornada: um estado de alto desempenho, onde o foco é inabalável e tudo parece fluir com naturalidade.

---

## 📝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir **Issues** ou enviar um **Pull Request** com melhorias, correções ou novas ideias.

1. **Faça um fork do repositório:**

   ```bash
   git fork https://github.com/Souferreira/Teste-No-Fluxo.git
   ```

2. **Crie um branch para sua funcionalidade/correção:**

   ```bash
   git checkout -b minha-contribuicao
   ```

3. **Envie suas alterações:**

   ```bash
   git push origin minha-contribuicao
   ```

4. **Abra um Pull Request** no repositório principal.

---

## 🧑‍💻 Autor

Desenvolvido por **Emanuel**. Entre em contato para dúvidas, sugestões ou parcerias!

---

## 📜 Licença

Este projeto está licenciado sob a **MIT License**.

---

## 🌟 Agradecimentos

A todos que incentivam o aprendizado e a busca por um estado de fluxo ideal. 🚀


   ```

<html lang="pt-BR">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Descubra seu Estágio no Fluxo</title>
 <style>
   /* Estilo Geral */
   body {
     font-family: Arial, sans-serif;
     display: flex;
     justify-content: center;
     align-items: center;
     height: 100vh;
     background: linear-gradient(90deg, #8e44ad, #9b59b6, #af7ac5);
     margin: 0;
     flex-direction: column;
   }
   .container {
     text-align: center;
     background-color: white;
     padding: 30px;
     box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
     border-radius: 8px;
     max-width: 400px;
   }
   h1 {
    background: linear-gradient(90deg, #eeeff1, #e3ecff, #d6e4ff);
    border: 5px solid #8d7fd5;
    border-radius: 30px;
    padding: 15px;
    transition: background-color 0.3s ease, transform 0.3s ease;
    text-align: center;
    color: #100909;
   }
   h1:hover{
    background: linear-gradient(90deg, #88afb5, #9ec7d7, #26a5db);
    transform: scale(1.05);

   }
   h2 {
    background: linear-gradient(90deg, #eeeff1, #e3ecff, #d6e4ff);
    border: 5px solid #8d8c91;
    border-radius: 30px;
    padding: 15px;
    transition: background-color 0.3s ease, transform 0.3s ease;
    text-align: center;
    color: #100909;
   }
   h2:hover{
    background: linear-gradient(90deg, #88afb5, #9ec7d7, #26a5db);
    transform: scale(1.05);
  }
   p:hover{
    background: linear-gradient(90deg, #88afb5, #9ec7d7, #26a5db);
    transform: scale(1.05);
  }
   p:hover{
    background: linear-gradient(90deg, #88afb5, #9ec7d7, #26a5db);
    transform: scale(1.05);
  }
   select, button {
     padding: 10px;
     font-size: 20px;
     margin-top: 20px;
     cursor:pointer;
     width: 100%;
     border: 4px solid #d72c2c;
     text-align: center;
     border-radius: 10px;
   }
   button {
    background: linear-gradient(90deg, #8b7e7d, #ae5b5b, #d71616);
     color: rgb(255, 253, 253);
     border: none;
   }
   button:hover {
    background: linear-gradient(90deg, #77bd6a, #77be8e, #26e146);
    transform: scale(1.05);
  }
   
   #resultado {
     margin-top: 20px;
     font-size: 18px;
     font-weight: bold;
     color: #333;
   }
   .explicacao {
     margin-top: 10px;
     font-size: 16px;
     color: #555;
   }
   .download-btn {
     margin-top: 20px;
     background-color: #28a745;
     color: white;
   }
   .download-btn:hover {
     background-color: #218838;
   }
 </style>
</head>
<body>
 <div class="container">
   <h1>Descubra o seu Estágio No Fluxo</h1>
   <h2>Instruções:</h2>
   <p>1. Seja honesto ao responder para obter um resultado mais preciso.</p>
   <p>2. Após o envio, você receberá o resultado importante o estágio em que está e dicas para avançar ao próximo nível.</p>
   <p>3. Vamos começar uma jornada rumo ao seu estado de fluxo ideal!</p>

   <select id="estagio">
     <option value="" selected>Selecione</option>
     <option value="a">Desmotivado e sem energia, como se estivesse em um estado de sonolência.</option>
     <option value="b">Entusiasmado e com vontade de começar, sentindo um despertar de energia.</option>
     <option value="c">Sobrecarregado com a quantidade de informações e demandas, sentindo-se um pouco perdido.</option>
     <option value="d">Focado em executar as tarefas, mas sem muita criatividade ou pensamento estratégico.</option>
     <option value="e">Organizando e planejando suas atividades, buscando otimizar seu tempo e recursos.</option>
     <option value="f">Completamente imerso na tarefa, executando-a sem pensar conscientemente, com fluidez e naturalidade.</option>
     <option value="g">Em um estado de fluxo constante, com alta performance e foco inabalável, sentindo que está no controle total.</option>
   </select>

   <button onclick="mostrarEstagio()">Mostrar Estágio</button>

   <div id="resultado"></div>
   <div id="explicacao" class="explicacao"></div>
   <button class="download-btn" id="downloadBtn" style="display: none;" onclick="baixarPDF()">Baixar PDF</button>
 </div>

 <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.4.0/jspdf.umd.min.js"></script>
 <script>
   const estagios = {
     '': { resultado: "Por favor, selecione um estágio válido!", explicacao: "" },
     'a': { resultado: "Estágio 1: Sonolência", explicacao: "A fase que sua mente está fechada(a), programada para ter os mesmos hábitos e atitudes, com medo de mudanças e dificuldades em dar o primeiro passo." },
     'b': { resultado: "Estágio 2: Despertar", explicacao: "Você começa a se sentir insatisfeito com algumas áreas da sua vida e busca tomar atitude, mas ainda não sabe por onde começar." },
     'c': { resultado: "Estágio 3: Sobrecarga de Informação", explicacao: "Você está consumindo muitas informações e se sente perdido sobre como colocar em prática o que aprendeu." },
     'd': { resultado: "Estágio 4: Execução sem Estratégia", explicacao: "Você começa a executar, mas sem um plano estratégico, o que te faz parar no meio do caminho ou se frustrar." },
     'e': { resultado: "Estágio 5: Organização e Planejamento", explicacao: "Você organiza e planeja suas atividades, buscando otimizar seu tempo e tomar decisões mais maduras." },
     'f': { resultado: "Estágio 6: Execução Fluida", explicacao: "Neste estágio, você começa a executar tarefas de forma fluida e contínua, sempre buscando a melhoria." },
     'g': { resultado: "Estágio 7: Fluxo Constante", explicacao: "Você atinge um estado de alto desempenho e foco constante, onde tudo parece fluir naturalmente, e você se sente no controle total." }
   };

   function mostrarEstagio() {
     const estagio = document.getElementById('estagio').value;
     const resultadoDiv = document.getElementById('resultado');
     const explicacaoDiv = document.getElementById('explicacao');
     const downloadBtn = document.getElementById('downloadBtn');

     if (estagios[estagio]) {
       resultadoDiv.innerHTML = `<p>${estagios[estagio].resultado}</p>`;
       explicacaoDiv.innerHTML = `<p>${estagios[estagio].explicacao}</p>`;
       downloadBtn.style.display = 'block';
     } else {
       resultadoDiv.textContent = "Selecione um estágio válido!";
       explicacaoDiv.textContent = "";
       downloadBtn.style.display = 'none';
     }
   }

   function baixarPDF() {
     const { jsPDF } = window.jspdf;
     const doc = new jsPDF();

     const resultado = document.getElementById('resultado').innerText;
     const explicacao = document.getElementById('explicacao').innerText;

     doc.setFontSize(16);
     doc.text("Resultado do Estágio no Fluxo", 10, 10);
     doc.setFontSize(14);
     doc.text(resultado, 10, 30);
     doc.text("Explicação:", 10, 50);
     doc.text(explicacao, 10, 60, { maxWidth: 190 });

     doc.save("resultado_fluxo.pdf");
   }
   
 </script>
</body>
</html>

```







