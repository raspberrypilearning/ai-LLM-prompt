## O processo OCEAN para escrever prompts: Personas

Personas são como diferentes papéis ou personagens que você pode pedir ao modelo de linguagem para assumir. Isso molda como ele interage com você. Por exemplo, você pode querer que o modelo pareça um professor amigável, um amigo prestativo, um personagem fictício ou uma figura histórica para ter uma conversa com você ou te ajudar a explorar algumas de suas próprias ideias. Usar uma persona permite que _cada_ interação com o LLM esteja em um contexto específico definido por você, não apenas o texto que ele produz.

### Objetivo

Decida qual papel você quer que o modelo de linguagem assuma. Escreva isso no seu pronto, indicando com clareza o papel que você deseja que ele desempenhe.

<span style="color: red;">Nos exemplos abaixo, o texto objetivo está em vermelho.</span>

### Contexto

Dê contexto em detalhe para ajudar o modelo a entender a função. Inclua informações específicas sobre como você quer que ele se comporte.

<span style="color: blue;">Nos exemplos abaixo, o texto de contexto está em azul.</span>

### Exemplos

Mostre que tipo de respostas você está procurando fornecendo **exemplos**. Isso ajuda o modelo a acertar. Você pode dar exemplos de coisas que você definitivamente quer incluir ou maneiras de falar que você gostou.

<span style="color: green;"> Nos exemplos abaixo, os exemplos são dados em verde.</span>

\--- task ---

Por exemplo: <span style="color: red;">"Comporte-se como um treinador que apoia e encoraja</span> <span style="color: blue;"> que ajuda a estudar para provas.</span> <span style="color: green;"> Dê dicas e conselhos motivacionais de pessoas inspiradoras. Por exemplo: 'Lembre-se, toda grande conquista começa com a decisão de tentar. Você consegue!’"</span>

\--- /task ---

\--- task ---

Por exemplo: <span style="color: red;">"Aja como um bibliotecário sábio e paciente</span> <span style="color: blue;"> que ajuda a encontrar livros e recursos interessantes.</span> <span style="color: green;"> Recomende livros com base em gêneros que eu goste. Por exemplo: 'Se você gosta de mistérios, talvez ame os romances de Agatha Christie. Eles são cheios de reviravoltas!'"</span>

\---/task---

\--- task ---

Por exemplo: <span style="color: red;">"Assuma o papel de um personal trainer energético</span> <span style="color: blue;"> que incentiva um estilo de vida saudável e exercícios diários.</span> <span style="color: green;"> Forneça rotinas de exercícios e citações motivacionais. Por exemplo: "Se esforce porque ninguém mais fará isso por você. Vamos começar com um aquecimento rápido!'"</span>

\---/task---

\--- task ---

Por exemplo: <span style="color: red;">"Finja ser um guru de tecnologia bem informado</span> <span style="color: blue;"> que dá conselhos sobre como usar novos gadgets e softwares.</span> <span style="color: green;"> Explique termos e conceitos de tecnologia de forma acessível, como um assistente robô amigável de um filme de ficção científica."</span>

\---/task---

### Avaliar

Verifique se a resposta corresponde ao que você queria. Procure erros ou coisas que não façam sentido.

\--- task ---

Por exemplo:

- A resposta soa como o papel que você descreveu?
- O tom é amigável e engraçado (ou o tom que você pediu)?
- Inclui os exemplos e detalhes que você mencionou?
- Há partes do texto erradas ou confusas?

\--- /task ---

### Negociar

Se a resposta não estiver certa, peça para o LLM fazer alterações. Seja específico sobre o que precisa ser corrigido.

\--- task ---

Sugira alterações e correções para o LLM.

Por exemplo:

"Isso é útil, mas, por favor, inclua mais citações motivacionais e use um tom mais amigável."
"Use palavras menos complicadas e explique as coisas como se eu fosse um iniciante."
"Seja mais positivo e construtivo no seu feedback."

\--- /task ---

### Etapa mais importante: A edição humana

\--- task ---

Verifique a resposta uma última vez para ter certeza de que é fácil de entender, correta e completa.

**É totalmente sua responsabilidade (a pessoa) garantir que a ferramenta que você está usando esteja funcionando corretamente e que o resultado dela não seja usado para causar danos.**

\--- /task ---
