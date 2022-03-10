# hse_hw2_chip
## Ссылка на google collab 
## Была выбрана клеточная линия MCF-7, гистоновая метка H3K9me3, 
## FastQC 
### ENCFF656BIN
![image](./images/1.png)
![image](./images/2.png)
![image](./images/3.png)
![image](./images/4.png)
Подрезание для этой реплики не требуется
### ENCFF517BLK
До подрезания
![image](./images/5.png)
![image](./images/6.png)
![image](./images/7.png)
![image](./images/8.png)
После подрезания:
![image](./images/9.png)
![image](./images/10.png)
![image](./images/11.png)
![image](./images/12.png)
### ENCFF318ZNB - с контролем
До подрезания
![image](./images/13.png)
![image](./images/14.png)
![image](./images/15.png)
![image](./images/16.png)
После подрезания:
![image](./images/17.png)
![image](./images/18.png)
![image](./images/19.png)
![image](./images/20.png)
## Выравнивание на хромосоме
Таблица со статистикой:
![image](./images/21.png)
Вероятно потому что мы выравниваем только по одной хромосоме
## Сравнение результатов
![image](./images/22.png)
![image](./images/23.png)
Пересечение считает число участков, которые имеются в первом файле, а также во втором. А соответсвенно при обратном наложении, наоброт те, которые есть во втором, а также в первом. Поэтому логично, что ответы разные.

