# Council-对议牌
新原创纸牌游戏的网页演示版，仅供演示游戏运行原理。在右上角可以切换语言。
游戏规则如下：
1.使用一副54张扑克牌(含大小王)
2.根据猜拳、翻牌、投硬币等方式分配先后手，玩家A为红方先手，玩家B为黑方后手，轮流扣牌。
3.每轮双方各扣置1或2张牌，牌面扣置时对对方不可见。
4.扣牌完成后双方展示扣牌，若扣牌颜色全同，则未拥有该颜色的玩家得1分。否则，计算红黑色各自的议事点数。议事点数等于对应颜色扣牌点数之和除以对应颜色的总张数(向上取整)，若扣置的牌有王牌则交换议事点数等同王牌数量次。王牌的点数为0，J，Q，K，A分别对应11，12，13，1。点数大者对应的玩家得1分，平局双方各得1分。
5.轮次最多27轮（牌堆用完游戏结束），或一方手牌为空游戏结束。
6.每轮后双方角色互换，颜色互换，先后手互换，得分绑定玩家不变。
7.玩家摸牌补充手牌至4张（不足则不摸，当轮红方先摸）。
8.你可以在网页查看相关议事点数计算。
议事点数计算公式：某颜色对应的议事点数=场上所有对应颜色的牌的点数总和/所有对应颜色的牌张数（结果向上取整）。
玩的开心！
——————————————————————————————
This is a web-based demo version of an original card game, designed solely to demonstrate its core mechanics. You can switch languages in the top right corner of the webpage.
Game Rules:
1.Deck: The game uses a standard 54-card poker deck, including both Jokers.
2.Determining First Player: You can decide who goes first using methods like rock-paper-scissors, a card flip, or a coin toss. Player A will be the Red Team and go first, while Player B will be the Black Team and go second. Players will then take turns placing cards face down.
3.Placing Cards: In each round, both players will secretly place either 1 or 2 cards face down. Your opponent won't be able to see the cards you've played.
4.Scoring: Once both players have placed their cards, they are revealed.
All Same Color: If all the revealed cards are the same color (either all red or all black), the player who doesn't have that color among their placed cards scores 1 point.
Mixed Colors: Otherwise, Council Points are calculated for both red and black cards separately. Deliberation Points are determined by dividing the sum of the points of the corresponding colored cards by the total number of cards of that color, then rounding up. If any Jokers are played, the Deliberation Points are swapped a number of times equal to the number of Jokers played. Jokers are worth 0 points. Jack (J), Queen (Q), King (K), and Ace (A) are worth 11, 12, 13, and 1 point respectively. The player whose color has the higher Deliberation Points scores 1 point. If there's a tie, both players score 1 point.
5.Game End: The game ends after a maximum of 27 rounds (when the deck runs out), or if one player's hand becomes empty.
6.Role Rotation: After each round, players will switch roles, colors, and who goes first. Your scores, however, remain tied to you as a player.
7.Drawing Cards: Players draw cards to replenish their hand to 4 cards. If there aren't enough cards left in the deck, they'll draw as many as possible. In each round, the current Red Team player draws first.
8.Real-time Calculation: You can view the real-time Deliberation Point calculations directly on the webpage.
Have fun!
