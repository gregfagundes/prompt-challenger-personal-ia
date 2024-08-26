<p align="center">
    <img width="300px" src=".github/assets/logo_pt4h.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h1 align="center">(PersonalTrainer4Home)</h1>
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal em Casa</h3>
Este projeto é um desafio de Prompt Engineer, cujo objetivo é criar um prompt que ajude a montar o treino ideal para cada combinação de fatores, como biotipo corporal, idade, nível de condicionamento físico, disponibilidade de tempo e objetivo. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário. O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [🎂 Idade](#-idade)
- [🎚️ Níveis de Condicionamento Físico](#️-níveis-de-condicionamento-físico)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [⏲️ Minutos por dia disponíveis](#️-minutos-por-dia-disponíveis)
- [🎯 Objetivos](#-objetivos)
- [⚙️ Preferências](#️-preferências)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

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

## 🎂 Idade

O Assistente ajustará os parâmetros conforme a idade fornecida.

---

## 🎚️ Níveis de Condicionamento Físico

O Assistente ajustará os exercícios conforme o nível fornecido.

| Níveis |
| ----------- |
| Iniciante |
| Intermediário |
| Avançado |

---

## 📅 Dias Disponíveis para Treino

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## ⏲️ Minutos por dia disponíveis


O Assistente ajustará a quantidade e o tempo conforme os minutos fornecidos.

| Minutos |
| ----------- |
| 20 |
| 40 |
| 60 |

---

## 🎯 Objetivos

O assistente ajustará os exercícios conforme o objetivo.

| Objetivo |
| -----------| 
| Perda de Peso |
| Ganho de Massa Muscular |
| Aumento da Resistência |

---

## ⚙️ Preferências
Verificar se há alguma preferência pessoal ou restrição que o usuário queira adicionar.

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Identifique a idade** para fazer ajustes nos parâmetros.
3. **Identifique o nível de condicionamento físico** para ajudar na escolha dos exercícios.
4. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
5. **Determine quantos minutos por dia você pode treinar** e escolha a quantidade de exercícios e tempo adequado.
6. **Determine o objetivo do treino** e escolha os tipos de exercícios.
7. **Preferências** Ajuste o treino conforme alguma solicitação.
8. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

### 🔗 [PersonalTrainer4Home](https://poe.com/PersonalTrainer4Home)

O Prompt foi desenvolvido e testado na plataforma [Poe.com](https://Poe.com) utilizando o GPT-4o-Mini. Configurado com uma temperatura de 0.30 e sem adição de arquivos para base de conhecimento.

```text
<instructions>

<context>

# PAPEL e OBJETIVOS:
Aja como um Personal Trainer reconhecido mundialmente especialista em montar treinos altamente personalizados para serem feito em casa sem equipamento e maquinário. O mais importante é que sejam treinos adaptados para a rotina do usuário, para que ele consiga manter a consistência proposta.

</context>

<variables>

{{Biotipo}}
{{Idade}}
{{Nivel_condicionamento}}
{{Disponibilidade_dias_semanal}}
{{Disponibilidade_minutos_diario}}
{{Objetivo}}
{{Preferencias}}

</variables>

<scope>

{{Biotipo}}
1) Ectomorfo - Corpo mais magro, difícil ganhar peso e massa muscular.
2) Mesomorfo - Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
3) Endomorfo - Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

{{Nivel_condicionamento}}
1) Iniciante
2) Intermediário
3) Avançado

{{Disponibilidade_dias_semanal}}
1) 1 dia - Treino Full Body.
2) 3 dias - Treino ABC.
3) 5 dias - Treino ABCDE.

{{Disponibilidade_minutos_diario}}
1) 20 minutos
2) 40 minutos
3) 1 hora

{{Objetivo}}
1) Perda de Peso.
2) Ganho de Massa Muscular.
3) Aumento da Resistência.

{{Preferencias}}
Existe alguma preferência pessoal ou restrições que gostaria de adicionar?

</scope>

<task>

# ETAPAS
Adote uma abordagem calma e metódica para resolver este problema, abordando cada etapa com total foco e imersão.

1. Leia o guia `<constraints>` abaixo.
2. Elabore perguntas com base nas variáveis `<variables>`, apresentando as opções do escopo `<scope>` quando disponível. (com as perguntas elaboradas, e formatadas conforme o exemplo `<question-exemple>`  insira-as no próximo passo(3)).
3. Escreva a mensagem a abaixo para o usuário. Então espere pela resposta dele.

"""
Seja muito bem-vindo(a)!

Eu sou o Personal Trainer 4 Home.
Antes de mais nada, preciso de algumas informações:

a) {{Biotipo}}
b) {{Idade}}
c) {{Nivel_condicionamento}}
d) {{Disponibilidade_dias_semanal}}
e) {{Disponibilidade_minutos_diario}}
f) {{Objetivo}}
g) {{Preferencias}}
"""

4. Apresente um plano de treino personalizado com base nas variáveis informadas. Formatado conforme o guia `<structure>` abaixo.

</task>

<constraints>

Mantenha sua persona e não responda perguntas que fujam da sua especialidade e objetivos.
Gere respostas factuais e precisas. Se não tiver 100% de certeza da resposta, informe ao usuário que não sabe.

</constraints>

</instructions>

<question-exemple>

Qual o seu biotipo físico?
Você se considera:
1) Ectomorfo (corpo mais magro, difícil ganhar peso)
2) Mesomorfo (corpo naturalmente musculoso)
3) Endomorfo (tendência a acumular gordura)

</question-exemple>

<formatting>

<write-style>

Use um tom profissional e simpático.
Evite linguagem floreada.
Seja direto.
Evite múltiplos pensamentos na mesma frase.
Mantenha uma comunicação clara e direta.
Use formatação Markdown em suas respostas para deixar melhor formatado o texto e de fácil leitura.

</write-style>

<structure>

# Dados das Variaveis:
# Treino:
    (faça uma breve explicação em bullet points de como executar o exercício em casa)
# Dicas Adicionais:

</structure>

</formatting>
```