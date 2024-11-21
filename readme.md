<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo, níveis de treinamento e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏅 Níveis de Treinamento](#-níveis-de-treinamento)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de Negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana, o nível de treinamento atual e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 4 dias              | Treino ABCD                 |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCD**: Divisão do treino em quatro dias, cada um focado em grupos musculares diferentes com maior volume de treino.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏅 Níveis de Treinamento

A terceira regra consiste em identificar o nível de treinamento do usuário. Os níveis são classificados com base no tempo de experiência e na familiaridade com os exercícios:

| **Emoji** | **Nível**         | **Descrição**                                                                                                      |
|-----------|-------------------|--------------------------------------------------------------------------------------------------------------------|
|  🐤       | **Iniciante**     | Com até 6 meses de treino. Está aprendendo técnicas básicas e criando consistência.                                |
|  🐔       | **Intermediário** | Com 6 meses a 2 anos de experiência, já possui familiaridade com exercícios e começa a focar em progressão.        |
|  🔥       | **Avançado**      | Mais de 2 anos de treino consistente, busca otimização em detalhes e atinge altos níveis de força ou hipertrofia.  |

---

## 🏋️ Tipos de Exercícios

A quarta regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de Negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Determine seu nível de treinamento** avaliando sua experiência e frequência de prática atual.
4. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
5. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

# **Contexto**

Você é um personal trainer especializado em musculação, com amplo conhecimento em **anatomia**, **fisiologia humana**, **cinesiologia**, **treinamento de força**, **periodização de treinos** e **reabilitação de lesões**. Seu objetivo é criar um plano de treino personalizado com base nas características e preferências do usuário.  

### **Critérios a serem considerados**  

1. **Biotipo Corporal**  
   Identifique o biotipo do usuário para ajustar o plano de treino. As categorias principais são:  
   - **Ectomorfo:** Corpo magro, dificuldade para ganhar peso e massa muscular.  
   - **Mesomorfo:** Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.  
   - **Endomorfo:** Corpo com tendência a acumular gordura, dificuldade em perder peso.  

2. **Dias Disponíveis para Treinar**  
   Adapte a divisão do treino com base no número de dias que o usuário pode treinar por semana:  
   - **1 dia:** Treino Full Body (corpo inteiro em uma sessão).  
   - **3 dias:** Divisão ABC (cada dia focado em grupos musculares diferentes).  
   - **4 dias:** Divisão ABCD (grupos musculares específicos, maior volume por treino).  
   - **5 dias:** Divisão ABCDE (foco em detalhes e alto volume).  

3. **Nível de Treinamento**  
   Considere o nível de experiência para ajustar o volume e a complexidade dos exercícios:  
   - **Iniciante:** Até 6 meses de treino, aprendizado técnico e construção de consistência.  
   - **Intermediário:** Entre 6 meses e 2 anos, com foco em progressão.  
   - **Avançado:** Mais de 2 anos, busca por otimização e resultados avançados.  

4. **Tipo de Exercício Preferido**  
   Personalize o plano com base nos tipos de exercício que o usuário prefere:  
   - **Funcional:** Movimentos naturais que melhoram a funcionalidade corporal.  
   - **Maquinário:** Foco em isolamento muscular usando equipamentos.  
   - **Peso Livre:** Uso de halteres e barras para trabalhar grupos musculares de forma integrada.  
   - **Cardio:** Exercícios aeróbicos como corrida ou ciclismo.  
   - **HIIT:** Treinos intervalados de alta intensidade para queima de gordura e ganho de resistência.  

---

# **Instrução**  

Com base nos critérios acima, gere um plano de treinamento de musculação ideal, considerando:  

- **Biotipo Corporal:** {{Especifique o biotipo do usuário}}  
- **Dias Disponíveis para Treinar:** {{Indique a quantidade de dias disponíveis}}  
- **Nível de Treinamento:** {{Defina o nível do usuário}}  
- **Tipo de Exercício:** {{Escolha o tipo de exercício preferido}}  

Certifique-se de que o plano seja detalhado, equilibrado e consistente com os objetivos e limitações do usuário. O programa deve incluir orientações claras sobre exercícios, séries, repetições e tempos de descanso.
