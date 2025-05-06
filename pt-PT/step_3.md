## O processo OCEAN de criar um prompt: Personas

Personas são como diferentes papéis ou personagens que podes pedir ao language model para assumir. Isto molda a forma que ele interage contigo. Por exemplo, podes querer que o modelo se pareça com um professor amigável, um amigo prestativo, um personagem fictício ou uma figura histórica e ter uma discussão contigo ou ajudar-te a explorar algumas das tuas ideias. Usar uma persona permite que **cada** interação com o LLM esteja num contexto específico que tenha sido definido por ti e não seja apenas o texto que ele produz.

### Objetivo

Decide que papel queres que o language model assuma. Escreve isso no teu prompt, indicando claramente o papel que queres que ele desempenhe.

<span style="color: red;">Nos exemplos abaixo, o texto do objetivo está a vermelho.</span>

### Contexto

Dá detalhes do contexto para ajudar o modelo a perceber o seu papel. Inclui informação específica sobre como queres que ele se comporte.

<span style="color: blue;">Nos exemplos abaixo, o texto do contexto está a azul.</span>

### Exemplos

Mostra que tipo de respostas estás à procura ao fornecer **exemplos**. Isto ajuda o modelo a acertar. Podes dar exemplos de coisas que pretendes mesmo incluir, ou maneiras de falar que gostes.

<span style="color: green;"> Nos exemplos abaixo, os exemplos estão a verde.</span>

\--- task ---

Por exemplo: <span style="color: red;">"Comporta-te como um treinador que apoia e encoraja</span> <span style="color: blue;">que ajuda a estudar para os exames.</span> <span style="color: green;">Dá dicas e conselhos motivacionais de pessoas inspiradoras. Por exemplo: ‘Lembra-te, cada grande conquista começa com uma decisão de tentar. Tu consegues!’"</span>

\--- /task ---

\--- task ---

Por exemplo: <span style="color: red;">"Representa um bibliotecário sábio e paciente</span> <span style="color: blue;">que ajuda a encontrar livros e recursos interessantes.</span> <span style="color: green;">Recomenda livros com base em géneros que eu gosto. Por exemplo: ‘Se gostas de mistérios, talvez gostes dos romances de Agatha Christie. Eles estão cheios de voltas e reviravoltas!’"</span>

\---/task---

\--- task ---

Por exemplo: <span style="color: red;">"Assume o papel de um preparador físico energético</span> <span style="color: blue;">que incentiva um estilo de vida saudável e exercício físico diário.</span> <span style="color: green;">Fornece rotinas de treino e mensagens motivacionais. Por exemplo: ‘Esforça-te porque mais ninguém o fará por ti. Vamos começar com um aquecimento rápido!’"</span>

\---/task---

\--- task ---

Por exemplo: <span style="color: red;">"Finge ser um guru da tecnologia bem informado</span> <span style="color: blue;">que dá conselhos sobre como usar novos dispositivos e programas.</span> <span style="color: green;">Explica os termos e conceitos tecnológicos duma maneira acessível, como um assistente robô amigável de um filme de ficção científica."</span>

\---/task---

### Avaliar

Verifica se a resposta corresponde ao que tu querias. Procura por erros ou coisas que não façam sentido.

\--- task ---

Por exemplo:

- A resposta soa como o papel que descreveste?
- O tom é amigável e divertido (ou qualquer outro tom que tenhas pedido)?
- Inclui exemplos e detalhes que mencionaste?
- Existe alguma parte do texto errada ou confusa?

\--- /task ---

### Negociar

Se a resposta não estiver totalmente certa, pede ao LLM para fazer alterações. Sê específico sobre o que precisas de corrigir.

\--- task ---

Sugere alterações e correções ao LLM.

Por exemplo:

"Isso é útil, mas, por favor, inclui mais mensagens motivacionais e num tom mais amigável.
"Usa menos palavras complicadas e explica as coisas como se eu fosse um principiante."
"Sê mais positivo e construtivo com o teu feedback."

\--- /task ---

### Passo mais importante: A edição humana

\--- task ---

Verifica as respostas uma última vez para teres a certeza que é fácil de seguir, correta e completa.

**A responsabilidade é toda tua (a pessoa) garantir que a ferramenta que estás a usar funciona corretamente e que o resultado não cause danos.**

\--- /task ---
