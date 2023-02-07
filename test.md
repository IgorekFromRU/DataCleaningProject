# MarkDown

## This is header

<strong> Hello Kineuron, </strong> *I think about it*\
$ formula: a_{i+1}=a_{i}+10 $

# Font
Наклонное и полужирное начертание в Markdown задаются при помощи символов * и _:

*italics*
**Bold**
___Bold&Italics___

# <center>Header 1</center>
## Horizontal line 2
-----------
### Header 3
#### Header 4
##### Header5
###### Header 6

## Ненумерованные списки можно использовать символы *, - или + —
+ One
    +  One.One
        - One.One.One
- Two
    - Two.Two
* Three 

1. First line 1
2. Second line 2

# ССЫЛКИ И ИЗОБРАЖЕНИЯ
* без подсказки — [текст ссылки](http://example.com/link);
* c подсказкой — [текст ссылки](http://example.com/link "Подсказка").

Для отображения изображений перед квадратными скобками ставfiится восклицательный знак:

![Hint](https://lms.skillfactory.ru/assets/courseware/v1/18688a72e30d95a3d4e0d9c92c43d64a/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/MDN_GIT_3_8.png)


<img src=https://proprikol.ru/wp-content/uploads/2022/06/chuvstvo-viny-prikolnye-kartinki-18.jpg width=500px height=30%>


# ПРОГРАММНЫЙ КОД И ЦИТИРОВАНИЕ
Для выделения программного кода используется обратный апостроф:

- одинарный парный — для вставки строки кода в текст;
- двойной парный — для вставки небольшого участка кода, содержащего одинарный апостроф, в текст;
- тройной парный — для вставки блока программного кода.
![Тильда и апостроф](https://lms.skillfactory.ru/assets/courseware/v1/3ace2a4c2e53d7f5d54e89e65d6b73aa/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/MDN_GIT_3_10.png "Подсказка").

`print('Hello world!')`

```python

lst = [10, 34, 21, 21, 3]

summa = sum(lst)

```

### Для оформления цитат используется знак «больше» (>):
> Цитируемый текст

### ФОРМУЛЫ
Воспользоваться символом $. Если обрамить формулу с обеих сторон одним символом $, то её можно встроить в текст, а если двумя — формула автоматически центрируется.

Пусть задано выражение:
$$a = b +c,$$
где $a=0$

* $\alpha$ — alpha
* $\gamma$ — gamma
* $\sigma$ — sigma

- $a^2$ —
- $b_{ij}$ —
- $w^{ij}_n$ —
- $\frac{1+x}{n}$ — 
- $\forall x \in X, \quad \exists y \leq \epsilon$
- $\alpha, \Alpha, \beta, \Beta, \gamma, \Gamma, \pi, \Pi, \phi, \varphi, \mu, \Phi$
- $\lim\limits_{x \to \infty} \exp(-x) = 0$

 Однако изучать и запоминать их всех вовсе не обязательно. Всегда можно найти, как записать то или иное математическое соотношение, в [документации по LaTeX](https://en.wikibooks.org/wiki/LaTeX/Mathematics "LaTeX").
