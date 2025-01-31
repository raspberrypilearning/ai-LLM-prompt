## Le processus de prompting OCEAN : Personas

Les personas sont comme différents rôles ou personnages que tu peux demander au modèle de langage d'adopter. Ceci façonne la façon dont il interagit avec toi. Par exemple, tu pourrais vouloir que le modèle adopte le rôle d'un enseignant sympathique, d'un ami serviable, d'un personnage fictif ou d'une figure historique et engage une discussion avec toi, ou t'aide à explorer certaines de tes idées. L'utilisation d'un persona permet à _chaque_ interaction avec le LLM d'être dans un contexte spécifique que tu définis, et pas seulement le texte qu'il génère.

### Objectif
Décide du rôle que tu veux que le modèle de langage adopte. Écris ceci dans ton prompt, en précisant clairement le rôle que tu veux qu'il joue.

<span style="color: red;">Dans les exemples ci-dessous, le texte objectif est en rouge.</span>

### Contexte
Donne des détails contextuels pour aider le modèle à comprendre le rôle. Inclus des informations spécifiques sur la façon dont tu veux qu'il se comporte.

<span style="color: blue;">Dans les exemples ci-dessous, le texte contextuel est en bleu.</span>

### Exemples
Montre le type de réponses que tu recherches en fournissant des **exemples**. Cela aide le modèle à le faire correctement. Tu peux donner des exemples de choses que tu veux absolument inclure, ou des façons de parler que tu as appréciées.

<span style="color: green;"> Dans les exemples ci-dessous, les exemples sont donnés en vert.</span>

--- task ---

Par exemple :
<span style="color: red;">« Comporte-toi comme un coach encourageant et solidaire</span>
<span style="color: blue;"> qui aide à réviser pour les examens.</span>
<span style="color: green;"> Donne des astuces et des conseils de motivation de personnes inspirantes. Par exemple : « N’oublie pas que chaque réussite commence avec la volonté d'essayer. Tu peux le faire ! »</span>

--- /task ---

--- task ---

Par exemple :
<span style="color: red;">« Agis comme un bibliothécaire sage et patient</span>
<span style="color: blue;"> qui aide à trouver des livres et des ressources intéressantes.</span>
<span style="color: green;"> Recommande des livres en fonction des genres que j'aime. Par exemple : « Si tu aimes les mystères, tu pourrais aimer les romans d’Agatha Christie. Ils sont pleins de rebondissements ! »</span>

---/task---

--- task ---

Par exemple :
<span style="color: red;">« Endosse le rôle d'un entraîneur de fitness énergique</span>
<span style="color: blue;"> qui encourage un mode de vie sain et un exercice quotidien.</span>
<span style="color: green;"> Fournis des routines d'entraînement et des citations motivantes. Par exemple : « Bouge-toi, car personne d’autre ne le fera à ta place. Commençons par un échauffement rapide ! »</span>

---/task---

--- task ---

Par exemple :
<span style="color: red;">« Fais semblant d'être un expert en technologie</span>
<span style="color: blue;"> qui donne des conseils sur l'utilisation des nouveaux gadgets et logiciels.</span>
<span style="color: green;"> Explique les termes et concepts technologiques de manière accessible, comme un assistant robot amical d'un film de science-fiction. »</span>

---/task---

### Évaluer
Vérifie si la réponse correspond à ce que tu souhaites. Recherche les erreurs ou les choses qui n’ont pas de sens.

--- task ---

Par exemple :

- La réponse ressemble-t-elle au rôle que tu as décrit ?
- Le ton est-il amical et drôle (ou quel que soit le ton que tu as demandé) ?
- Est-ce que cela inclut les exemples et les détails que tu as mentionnés ?
- Y a-t-il des parties du texte qui sont fausses ou confuses ?

--- /task ---

### Négocier
Si la réponse n’est pas tout à fait correcte, demande au LLM d’apporter des modifications. Sois précis sur ce qui doit être corrigé.

--- task ---

Propose des modifications et des corrections au LLM.

Par exemple :

« Ceci est utile, mais inclus des citations plus motivantes et adopte un ton plus amical. »
« Utilise des mots moins compliqués et explique les choses comme si j'étais un débutant. »
« Sois plus positif et constructif dans tes commentaires. »

--- /task ---

### Étape la plus importante : la modification faite par un humain

--- task ---

Vérifie la réponse une dernière fois pour t'assurer qu'elle est facile à suivre, correcte et complète.

**Il t'appartient de t'assurer que l'outil que tu utilises fonctionne correctement et que les résultats qu'il produit ne sont pas utilisés pour causer du tort.**

--- /task ---
