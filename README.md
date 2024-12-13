
# Descubra seu Estágio no Fluxo

Este é um projeto interativo em HTML, CSS e JavaScript que permite ao usuário identificar o estágio em que está em sua jornada rumo ao estado de fluxo ideal. Ao selecionar um estágio, você receberá uma explicação sobre sua situação atual e dicas para avançar para o próximo nível.

---

## 🔍 Sobre o Projeto

A ideia central do projeto é ajudar as pessoas a se identificarem em uma das fases de progresso pessoal ou profissional, com base em como se sentem atualmente em relação às suas tarefas, foco e produtividade. O objetivo é orientar o usuário a entender seu estado e fornecer dicas para alcançar um estado de **alto desempenho** e **fluxo constante**.

O projeto é simples e utiliza HTML, CSS e JavaScript puro, sendo ideal para iniciantes explorarem conceitos básicos de **design responsivo**, **manipulação DOM** e **lógica interativa**.

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

Abaixo está a estrutura básica do projeto:

📂 DescubraSeuEstagioNoFluxo ├── index.html # Arquivo principal com o conteúdo e a estrutura HTML ├── style.css # Estilos gerais aplicados ao projeto └── script.js # Lógica interativa do projeto

---

## 🚀 Como Executar o Projeto

1. Faça o clone do repositório:
   ```bash
   git clone (https://github.com/Souferreira/Teste-No-Fluxo.git)
2. Navegue até o diretório do projeto:
     ```bash
   cd DescubraSeuEstagioNoFluxo
4. Abra o arquivo no seu navegador de preferência.
      ```bash
   Indexatualizado.html


## 📖 Estágios Explicados

1️⃣ Sonolência
Você se sente desmotivado e sem energia, como se estivesse em um estado de sonolência. Há dificuldade em dar o primeiro passo para mudanças.

2️⃣ Despertar
Uma insatisfação inicial surge, acompanhada de um desejo de mudança, mas ainda sem saber por onde começar.

3️⃣ Sobrecarga de Informação
Muitas informações foram absorvidas, mas a quantidade parece esmagadora, gerando confusão sobre como agir.

4️⃣ Execução sem Estratégia
Há ação, mas sem planejamento, levando a frustrações ou pausas frequentes no processo.

5️⃣ Organização e Planejamento
O foco passa a ser organizar e planejar de forma eficiente, buscando melhorar o uso do tempo e dos recursos.

6️⃣ Execução Fluida
Você começa a executar as tarefas com fluidez e naturalidade, alcançando melhorias constantes.

7️⃣ Fluxo Constante
O ápice da jornada: um estado de alto desempenho, onde o foco é inabalável e tudo parece fluir com naturalidade.

📝 Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir Issues ou enviar um Pull Request com melhorias, correções ou novas ideias.

Faça um fork do repositório.
Crie um branch para sua funcionalidade/correção:
bash
Copiar código
git checkout -b minha-contribuicao
Envie suas alterações:
bash
Copiar código
git push origin minha-contribuicao

## 🧑‍💻 Autor
Desenvolvido por Emanuel.
Sinta-se à vontade para entrar em contato para dúvidas, sugestões ou parcerias!

## 📜 Licença
Este projeto está licenciado sob a MIT License.

## 🌟 Agradecimentos
A todos que incentivam o aprendizado e a busca por um estado de fluxo ideal. 🚀


## 📝 Código Fonte
Abaixo está o código-fonte completo do projeto:
 ```bash

<!DOCTYPE html>
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
      background-color: #f5f5f5;
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
      color: #333;
    }
    h2 {
      color: #555;
      margin-bottom: 10px;
    }
    p {
      color: #666;
      margin: 5px 0;
    }
    select, button {
      padding: 10px;
      font-size: 16px;
      margin-top: 20px;
      cursor: pointer;
      width: 100%;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #007BFF;
      color: white;
      border: none;
    }
    button:hover {
      background-color: #0056b3;
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
  </style>
</head>
<body>
  <div class="container">
    <h1>Descubra o seu Estágio No Fluxo</h1>
    <h2>Instruções:</h2>
    <p>- Seja honesto ao responder para obter um resultado mais preciso.</p>
    <p>Após o envio, você receberá o resultado importante o estágio em que está e dicas para avançar ao próximo nível.</p>
    <p>Vamos começar uma jornada rumo ao seu estado de fluxo ideal!</p>

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
  </div>

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

      if (estagios[estagio]) {
        resultadoDiv.innerHTML = `<p>${estagios[estagio].resultado}</p>`;
        explicacaoDiv.innerHTML = `<p>${estagios[estagio].explicacao}</p>`;
      } else {
        resultadoDiv.textContent = "Selecione um estágio válido!";
        explicacaoDiv.textContent = "";
      }
    }
  </script>
</body>
</html>



