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

<p align="justify">
  <h3 align="center">🏋️‍♂️ Assistente de Calistenia - Gerador de Treino Ideal em Praças Públicas</h3>
Este projeto é um desafio de Prompt Engineering avançado, onde o objetivo é criar um prompt que gera um plano de treino de calistenia personalizado para ser realizado em praças públicas. O assistente considerará o biotipo corporal, IMC, idade, gênero, disponibilidade de tempo, nível de condicionamento físico e equipamentos disponíveis em praças públicas para criar um programa de treino eficaz e adaptável. O projeto deve ser feito utilizando as boas práticas de prompt engineering.
</p>

## 📋 Índice

- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📊 Índice de Massa Corporal (IMC)](#-índice-de-massa-corporal-imc)
- [🎂 Idade e Gênero](#-idade-e-gênero)
- [📅 Disponibilidade para Treino](#-disponibilidade-para-treino)
- [🏋️ Níveis de Condicionamento](#️-níveis-de-condicionamento)
- [🛠️ Equipamentos em Praças Públicas](#️-equipamentos-em-praças-públicas)
- [📊 Progressão de Exercícios](#-progressão-de-exercícios)
- [🌡️ Adaptações Climáticas](#️-adaptações-climáticas)
- [🥗 Dicas Nutricionais](#-dicas-nutricionais)
- [🛠️ Regras de Negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

## 📝 Introdução

<p align="justify">
Este projeto visa criar um assistente de calistenia automatizado que gera treinos personalizados para serem realizados em praças públicas. O usuário fornecerá informações sobre seu biotipo corporal, IMC, idade, gênero, disponibilidade de tempo, nível de condicionamento físico e equipamentos disponíveis na praça pública de sua escolha. O assistente então criará um plano de treino ideal, considerando essas variáveis e as particularidades do treinamento ao ar livre.
</p>

## 💪 Biotipos Corporais

<p align="justify">
A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:
</p>

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

<p align="justify">
> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.
</p>

## 📊 Índice de Massa Corporal (IMC)

<p align="justify">
O IMC é uma métrica importante para determinar a intensidade e o tipo de exercício adequado. Ele é calculado dividindo o peso (em kg) pela altura (em metros) ao quadrado.
</p>

| Categoria de IMC | Descrição                      |
|------------------|--------------------------------|
| Abaixo do peso   | IMC < 18,5                     |
| Peso normal      | 18,5 ≤ IMC < 24,9              |
| Sobrepeso        | 25 ≤ IMC < 29,9                |
| Obesidade        | IMC ≥ 30                       |

## 🎂 Idade e Gênero

<p align="justify">
A idade e o gênero influenciam na escolha dos exercícios e na intensidade do treino. O assistente ajustará o plano de acordo com as faixas etárias e considerações de gênero.
</p>

## 📅 Disponibilidade para Treino

<p align="justify">
A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:
</p>

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido**                            |
| -------------------------------------------------------------- | ------------------- | ------------------------------------------------------ |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 2-3 dias            | Treino de Corpo Inteiro                                |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 4-5 dias            | Divisão por Grupos Musculares (Push/Pull/Legs)         |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 6-7 dias            | Rotina Avançada com Dias de Especialização             |

## 🏋️ Níveis de Condicionamento

| Nível           | Descrição                                           |
|-----------------|-----------------------------------------------------|
| Iniciante       | Pouca ou nenhuma experiência em calistenia           |
| Intermediário   | Capaz de realizar exercícios básicos com boa forma   |
| Avançado        | Domínio de movimentos complexos e variações          |

## 🛠️ Equipamentos em Praças Públicas

| Equipamento     | Exercícios Possíveis                                |
|-----------------|-----------------------------------------------------|
| Barras          | Pull-ups, Muscle-ups, Leg raises                    |
| Paralelas       | Dips, L-sits, Handstand push-ups                    |
| Bancos          | Step-ups, Decline push-ups, Bulgarian split squats  |
| Escadas         | Subida de escadas, Mountain climbers                |

## 📊 Progressão de Exercícios

| Exercício Base  | Progressões                                         |
|-----------------|-----------------------------------------------------|
| Push-up         | Inclinado → Padrão → Declinado → One-arm            |
| Pull-up         | Negativas → Assistido → Padrão → Weighted → One-arm |
| Squat           | Assisted → Bodyweight → Pistol → Weighted Pistol    |

## 🌡️ Adaptações Climáticas

<p align="justify">
As condições climáticas podem afetar o desempenho e segurança durante os treinos. Aqui estão algumas adaptações sugeridas:
</p>

| Clima           | Adaptações Sugeridas                                |
|-----------------|-----------------------------------------------------|
| Calor Intenso   | Treinos mais curtos, foco em hidratação             |
| Frio Extremo    | Aquecimento prolongado, camadas de roupa            |
| Chuva Leve      | Exercícios sob áreas cobertas, grip training        |

## 🥗 Dicas Nutricionais

<p align="justify">
A nutrição é um componente essencial para alcançar seus objetivos de fitness. Aqui estão algumas recomendações baseadas em diferentes objetivos:
</p>

| Objetivo        | Recomendações Nutricionais                          |
|-----------------|-----------------------------------------------------|
| Ganho Muscular  | Superávit calórico, foco em proteínas e carboidratos|
| Perda de Gordura| Déficit calórico moderado, alta ingestão proteica   |
| Manutenção      | Equilíbrio calórico, dieta balanceada               |

## 🛠️ Regras de Negócio

<p align="justify">
Para garantir que o plano de treino seja eficaz e seguro, siga estas etapas:
</p>

1. Identifique seu biotipo corporal consultando a seção de biotipos.
2. Calcule seu IMC e veja em qual categoria você se encaixa.
3. Informe sua idade e gênero para ajustes personalizados.
4. Determine quantos dias por semana você pode treinar e escolha o tipo de treino mais adequado.
5. Identifique seu nível de condicionamento físico atual.
6. Liste os equipamentos disponíveis na praça pública escolhida.
7. Considere as condições climáticas típicas da sua região.
8. Defina seu objetivo principal (ganho muscular, perda de gordura, etc.).
9. Use o prompt do assistente para gerar um plano de treino personalizado.

## 📖 Material de Apoio

<p align="justify">
Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:
</p>

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)
- [Guia Completo de Calistenia](https://www.calistenia.net/)
- [Nutrição para Praticantes de Calistenia](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5872783/)
- [Treinamento ao Ar Livre: Benefícios e Desafios](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3710158/)

## 🎯 Prompt de Resposta Proposto

<p align="justify">
Você é um Assistente de Calistenia especializado em criar planos de treino para serem realizados em praças públicas. Com base nas informações fornecidas pelo usuário, crie um plano de treino detalhado e personalizado seguindo estas diretrizes:
</p>

1. Cumprimente o usuário e peça as informações necessárias (biotipo, IMC, idade, gênero, disponibilidade, nível, equipamentos disponíveis, clima típico e objetivo).

2. Analise as informações e crie um plano de treino semanal que inclua:
   - Aquecimento específico para o ambiente externo
   - Exercícios principais com progressões adequadas
   - Variações para diferentes condições climáticas
   - Dicas de segurança para treinar em espaços públicos

3. Forneça um cronograma detalhado com sets, repetições e tempos de descanso.

4. Inclua dicas nutricionais alinhadas com o objetivo do usuário.

5. Ofereça sugestões para monitorar o progresso e ajustar o plano conforme necessário.

6. Conclua com palavras de encorajamento e ofereça-se para esclarecer dúvidas ou fazer ajustes no plano.

<p align="justify">
Lembre-se de manter um tom profissional, motivador e educativo, enfatizando a importância da consistência e da técnica correta na prática da calistenia.
</p>
