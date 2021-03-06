**1.** Да се реализира клас **Building** (сграда), който се описва със следните характеристики:

- застроена площ в м2(цяло положително число)

- брой етажи (цяло положително число).

За него да се реализират:

- конструктор по подразбиране и конструктор с параметри

- подходящи селектори и мутатори;

- метод **getTotalArea** , който изчислява и връща разгърнатата площ (застроена площ x брой етажи);

- метод **getHeight** , който изчислява и връща височината на сградата (брой етажи x 4 метра);

- оператор \&lt;, който сравнява 2 сгради по височина и връща true, ако първата е по-ниска от втората, иначе връща false;

- оператор \&lt;\&lt;, който извежда информацията за сградата по подходящ начин на изходен поток.

**2.** Да се реализира производен клас House (къща), която допълнително задава:

- брой стаи(цяло положително число);

- собственик (низ с произволна дължина).

За него да се реализират:

- голямата четворка;

- подходящи селектори и мутатори;

- оператор \&lt;, който сравнява 2 къщаи по брой стаи и връща true, ако първата има по-малко стаи от втората, иначе връща false;

- оператор \&lt;\&lt;, който извежда информацията за блока по подходящ начин на изходен поток.

**3.** Да се напише главна програма, в която:

- да се дефинират поне 2 блока;

- да се изведе информацията за тях;

- да се сравнят по височина и по брой апартаменти.
