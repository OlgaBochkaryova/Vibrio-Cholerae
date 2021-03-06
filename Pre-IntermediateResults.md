# Table of Contents
1. [GC-skew](#GC-skew)
2. [Синтенные Блоки](#Синтенные Блоки)
3. [Деревья](#Деревья)
4. [Однохромосомные](#Однохромосомные)


15 геномов, из них 2 однохромосомные(Vibrio cholerae strain 10432-62, Vibrio cholerae strain 1154-74), 1 трёххромосомный (Vibrio cholerae strain TSY216), и 1 - с плазмидой (Vibrio cholerae strain 2012EL-2176). Два генома одного серотипа: Vibrio cholerae O395.  

#GC-skew
Есть несколько типов:  

1. GC-skew нормальной хромосомы (1-ая, большая)  
![](https://cloud.githubusercontent.com/assets/12018612/18810616/105faf88-82ac-11e6-9a46-ace57932bdc5.jpg)

2. Очень часто 2-ая хромосома выглядит так, со странным изломом:  
![](https://cloud.githubusercontent.com/assets/12018612/18810622/239c0948-82ac-11e6-88b8-20133cf9edde.jpg)

3. 3-я хромосома, по сути, большая плазмида:  
![](https://cloud.githubusercontent.com/assets/12018612/18810623/23b06622-82ac-11e6-9cb1-5360e3ac9dac.jpg)

4. Собственно, плазмида:  
![](https://cloud.githubusercontent.com/assets/12018612/18810620/2398088e-82ac-11e6-996d-8a77da9e256d.jpg)

5. Интересные однохросомные:  
![](https://cloud.githubusercontent.com/assets/12018612/18810621/239811b2-82ac-11e6-8a3e-7d91e458a933.jpg)

#Синтенные Блоки:
Вообще все блоки:
> All  98	91.28%

Те, которые есть у всех по одному экземпляру:
> All  24	92.03%

Среди тех блоков, которые общие, скачков нет, они либо все на 1-ой, либо все на 2-ой(ну, кроме однохромосомных, у них всё на одной). 3-ья хромосома ничего общего с остальными не имеет.

Среди всех-всех блоков есть совсем немного качующих, что там -- я не смотрела (длина блока > 5k).

#Деревья:
Построенное muscle:  
![](https://cloud.githubusercontent.com/assets/12018612/18814609/0b075576-832a-11e6-821d-ccca7a5e79c6.jpg)
Bootstraps, полученные с помощью phylip:  
<pre>
                                                          +-------CP003069  
                                                  +-100.0-|
                                          +--78.0-|       +-------CP007634  
                                          |       |
                                  +-100.0-|       +---------------CP001485  
                                  |       |
                                  |       +-----------------------CP000626  
                          +-100.0-|
                          |       |                       +-------CP006947  
                          |       |               +-100.0-|
                          |       +---------100.0-|       +-------CP010811  
                  +-100.0-|                       |
                  |       |                       +---------------CP010812  
                  |       |
                  |       |                               +-------AP014524  
          +--77.0-|       +-------------------------100.0-|
          |       |                                       +-------CP002555  
          |       |
          |       |                                       +-------CP001235  
          |       |                               +-100.0-|
  +-------|       +--------------------------99.0-|       +-------CP009042
  |       |                                       |
  |       |                                       +---------------CP003330
  |       |
  |       |                                               +-------AE003852
  |       +------------------------------------------77.0-|
  |                                                       +-------CP007653
  |
  +---------------------------------------------------------------CP001233
</pre>

Эти деревья отличаются одной веткой: CP003330 Vibrio cholerae IEC224  

Так выглядит дерево с отмеченными параллельными событиями (надо нарисовать в другой программе):
![](https://cloud.githubusercontent.com/assets/12018612/18814904/5dda04e0-8331-11e6-8ea1-d87d09486da6.jpg)


#Однохромосомные:
Выделенные участки гомологичны второй хромосоме предковой формы (по результатам мгры):  
##Vibrio cholerae strain 1154-74  
circular chromosome of length 68 follows:  
-11 -2 -9 +25 +66 +36 -39 +55 -17 +29 +35 -16 +19 +23 -49 -24 -50 -60 +67 +4 -15 +44 +43 -28 -46 +61 -32 -20 +18 -27 +26 -21 +98 -56 +38 -12 +54 -59 +14 **+13 -71 +57 -37 +65 +58 -34 -5 -3 -53 -63 -62 -51 +48 -30 -8 +70 -45 +33 +47 -7 -31 +41** -52 +40 -22 +6 +42 +72 @  
##Vibrio cholerae strain 10432-62  
circular chromosome of length 68 follows:  
-11 -2 -9 +25 +36 -39 +55 -17 +29 -26 +76 +27 -18 +20 +32 -61 +46 +28 -43 -44 +15 -4 +60 +50 +24 +49 -23 -19 +16 **+62 +53 +64 +3 +5 +68 +34 -58 +37 -69 -57 +71 -13 -41 +31 +7 -47 -33 +45 +8 +30 -48 +51** -35 -21 +98 -56 +38 -74 -12 +54 -59 +14 -52 +40 -22 +6 +42 +72 @  

##Предковая 2-ая хромосома:  
circular chromosome of length 27 follows:  
**-13 -41 +31 +7 -80 -47 -33 +45 -70 +8 +30 -48 +51 +62 +63 +53 +64 +3 +5 +68 +34 -58 -65 +37 -69 -57 +71**@  



