# hse_hw2_chip
<h3> Ссылка на google colab 1 </h3>
https://colab.research.google.com/drive/1x_j6ZN8T43TqhYYFPBgRwfirY3p78SWU?usp=sharing

Клеточная линия: HUES48
Гистоновая метка: H3K9ac

<h3> FastQC </h3

Качество нуклеотидов в большинстве случаев находится в зеленой зоне, есть и небольшое количество в оранжевой. Распределения GC состава близки к теоретическим распределениям. Можно сказать, что в целом чтения неплохие. 
  
1 реплика (ENCFF499KLD)

![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/KLD_1.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/KLD.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/KLD_3.PNG)

2 реплика (ENCFF813ERY)

![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/ERY_1.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/ERY_2.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/ERY_3.PNG)

Контроль (ENCFF693RXC)

![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/RXC_1.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/RXC_2.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/c9e83cd96515ba03b12034bfcc79be50b4f9971f/img/RXC_3.PNG)

<h3> Статистика по чтениям </h3>

| Образец | Всего ридов | Выравнялось уникально | Выравнялось неуникально | Не выравнялось | 
|---|---|---|---|---|
| ENCFF499KLD   | 42889997 | 1604174 (3.74%)  |4318887 (10.07%) |36966936 (86.19%)|
| ENCFF813ERY   | 26437338 | 1068806 (4.04%)  |3270848 (12.37%) |22097684 (83.59%)|
| ENCFF693RXC   | 42675605 | 1790757 (4.20%)  |5401032 (12.66%) |35483816 (83.15%)|

Из тыблицы выше видно, что процент тех, которые не выравнились больше, чем процент выравненных. Это связано с тем, что варавнивание производилось на одну хромосому. 

<h3> Диаграммы Венна </h3>

![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/14be6922f43838423ba208efd7bc159ed019ccd2/img/v1.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/14be6922f43838423ba208efd7bc159ed019ccd2/img/v2.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/14be6922f43838423ba208efd7bc159ed019ccd2/img/v3.PNG)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/14be6922f43838423ba208efd7bc159ed019ccd2/img/v4.PNG)

Из диаграмм видно, что количество пересекающихся учатсков небольшое. Это связано с тем, что изначально у нас небольшое количество пиков. 
Количество пересечений на диаграммах рассматриваемых пиков с пиками ENCODE и в пересечении пиков ENCODE с рассматриваемыми разное, так как сначала считается число рассмматриваемых пиков, которые есть в файле с пиками ENCODE; в другом случае считаются пики ENCODE, которые есть в файле с рассматриваемыми пиками. 

<h3> Бонус </h3>

![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/67415bd3e6f8d643922d4aac87bdcf70d380d1e5/img/%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20(3).png)
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/67415bd3e6f8d643922d4aac87bdcf70d380d1e5/img/%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20(4).png)

Не нашла на предложенной картинке свою гистоновую метку. Ориентировалась на картинку: https://www.cell.com/trends/biochemical-sciences/comments/S0968-0004(10)00094-0
![](https://github.com/ZhukovaJul/hse_hw2_chip/blob/91e2ecca29689ccb65e0dc67ca9bd74e96a263a9/img/gr1.jpg)

Активность на построенном графике в целом сходится с приведенным примером. И там, и там есть два пика, первый из которых ниже. Различие состоит в том, что на полученном нами графике идет плавное снижение, в то время как на приведенном пример оно резкое. 
