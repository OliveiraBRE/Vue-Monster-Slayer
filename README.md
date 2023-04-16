#Monster Slayer

Rápida descrição do objetivo de fazer esse projeto

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Monster Slayer**
| :label: Tecnologias | html, css, javascript & Vue.js

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://cdn.discordapp.com/attachments/1097012452580929656/1097012508721692692/monsterSlayer.png#vitrinedev) 



## Detalhes do projeto (Project details)


**Português:** No início, tanto o Monster quanto o player possuem uma barra de vida completa (100 pontos para cada). Inicialmente o player possue três alternativas para o primeiro turno do combate.

**English:** At beginning, Monster and player get full life bar (100 points for each) and the player has three alternatives in first combat turn.

![](https://cdn.discordapp.com/attachments/1097012452580929656/1097025430504099891/startGame.png)

**Português:** A cada interação com o game, o player sofrerá um ataque do Monster (controlado pela máquina) - que varia entre 5 e 12 pontos de dano - e terá uma baixa de sua barra de vida, e a cada ataque que o player executar. O Monster também terá baixa em sua barra de vida se o player atacar, a battle log trará a quantidade de dano que ambos sofreram em ordem do mais recente para o mais antigo ataque executado.

**English:** Each game interaction, the player going to get a Monster attack (Monster is controlled by machine) - into a ranger 5 and 12 points - and will get life bar downing. The Monster will get life bar downing if player execute a attack action, battle log going to get damage quantity both suffered, the attack is ordered in the most recent to oldder attack.

![](https://cdn.discordapp.com/attachments/1097012452580929656/1097029654029807697/attack.png)

**Português:** Mesmo ao se curar, o player também sofrerá dano no turno, no entanto não efetuará nenhum ataque, e a battle log registrará a ação de curar-se em destaque.

**English:** Even healing himself, the player going to suffer a turn attack from Monster but he does not executing any attack and the battle log going to register heal action with prominence. 

![](https://cdn.discordapp.com/attachments/1097012452580929656/1097035149478215710/heal.png)

**Português:** A cada 3 turnos o botão "special attack" será liberado, o que causará um dano de 10 a 20 no Monster, caso "special attack" não seja utilizado, o botão retorna ao estado de desabilitado.

**English:** Each 3 turns, "special attack" button going to be enable and it will be able cause an attack between a range 10 to 20 damage in Monster, case "special attack" button not be used it returning to disable state.

![](https://cdn.discordapp.com/attachments/1097012452580929656/1097037666152882246/specialAttack.png)

**Português:** O jogo termina em uma das seguites possibilidades: o player ganha

**English:** The game ends among following possibilities: the player wins

![](https://cdn.discordapp.com/attachments/1097012452580929656/1097038712417824888/playerVictory.png)

**Português:** o player perde

**English:** the player loses

![](https://cdn.discordapp.com/attachments/1097012452580929656/1097039396512993371/monsterVictory.png)

**Português:** ou empate.

**English:** or draw.

![](https://cdn.discordapp.com/attachments/1097012452580929656/1097040293498474566/draw.png)

**Português:** Caso o botão surrender seja acionado, o jogo finaliza imediatamente e concede vitória ao Monster. O botão "New Game" reseta o jogo e disponibiliza uma nova partida

**English:** Case surrender button be pressed, the game finishes immediately and granting Monster victory. "New Game" button goin to restart the match.


## Conquistas e Próximos Passos (Conquest & Next Steps)

**Português:** Este projeto foi contruído em Vue.js e Vanilla Javascript, foi empregado os conceitos básicos da framework: métodos data(), methods, computed e watch do Vue.createApp(); e as directives v-bind e v-on (em suas respectivas shorthands), v-if e v-for. Estes conceitos foram bem internalizados e seu uso foi bem compreendido.
O próximo tópico a ser estudado será a criação e uso dos componentes.

**English:** This project was built in Vue.js and Vanilla Javascript, being used framework core concepts: data(), methods, computed and watch methods from Vue.createApp(); and following directives: v-bind and v-on (in respectives shorthands), v-if and v-for. This concepts were well internilize and they use case was well understood.
Next topic studying going to be creating and using components.

