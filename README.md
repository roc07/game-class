1. Цел и функционалност на играта

- Играта представлява "мениджмънт" на един или двама участници в дуел.

- Играчът има правото да избере между различни опции, които да му дадат определени предимства и/или недостатъци. Пример за това:
* избираме да използваме Герой (cl2 hero), който ще е мъж (cl2 hero.gender) което ще го направи по-силен (cl2 hero.strength), но не толкова гъвкав (cl2 hero.agility). Героят ще използва меч (cl8 weapon.sword) и щит (cl9 armor.shield), които му дава орпеделени статистики като . Ще използва някакво умение (cl10 ability...) и тн.
* противника му ще е Бандит (cl3 enemy), който ще е... и ще използва... 

- И двата персонажа (в случая Герой и Бандит) трябва да могат да се създават или на ръка от играча или да се генерират автоматично на случаен (random) принцип от компютъра. 
- Създаването на персонаж от човек ще става чрез конзолата, с прост изборен метод пример:
Click for example 1
след което играчът получава следващата опция, примерно за години на героя и тн.
- При автоматичното създаване, ще се използва random генератора на c#, който да избира за всяка опция число в диапазон (1 до 10 примерно за оръжията, 1 до 3 за броня и тн).

- Самият двубой ще се изчислява от компютъра според зададените му условия и статистиките на създадените персонажи.


2. Информация за Класове

- Три нива на йерархия и наследяемост - Creatures > Heroes / Monsters > Warrior / Mage / Monster / Bandit 


3. Event 

- On key pressed? "space" - спира програмата или добавя сила на героя за 5 секунди или прави някакъв "event" на рандом (изписва на конзолата "сградата в която се води двубоя започва да се руши, Героя взима 10 damage).
 
