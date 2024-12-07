Ce qu'il me faut faire :
- je vais pouvoir faire jouer le bot contre lui-même ; façon RL
- Il me faut une bonne fonction de coût voire optimiser bêtement pour voir ce que ça donne. Un simple algo de RL serait, dans un premier temps, suffisant.
- Dans un second temps, une fois que je suis satisfait, je cherche à vraiment respecter les limitations imposées...

Cela pourra inclure :
- quantization
- ...

Je vais commencer par :
1) algo baseline qui apprend
2) code d'entraînement : mini-batch ? (i.e. je joue 5 fois et je fais une descente de gradient) -> au moins une fois blanc, une fois noir... A voir... On peut faire de multiples agents. On vient loader le bon.
3) Code de suivi des métriques etc. tout un tas de choses pour savoir un peu comment ça se passe.

Distillation ?
i.e. brute force distille à un petit modèle RL. Ainsi, on lui donne les meilleurs coups.

Il me faut donc réfléchir un peu plus à tout cela.
