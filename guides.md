# Соглашения о разметке   

1. В тексте размечаются как предикаты практически все  
* глаголы (VERB)   
* предикативы (*скок*, *жаль*) (VERB)  
* имена существительные (кроме имен собственных и названий конкретных реалий) (NOUN)  
* имена прилагательные (кроме имен географических сущностей), местоимения-прилагательные (ADJ, DET)  
* наречия (ADV)  
* предлоги (ADP)  
* междометия (INTJ)  

2. Не размечаются как предикаты:  
* отрицание  
* числительные   
* личные местоимения  
* анафорические местоимения (размечаются на уровне разметки анафоры)   
* указательные слова *этот*, *тот*   

3. Как аргумент размечается синтаксическая вершина той группы, которая является аргументом предиката. Если это клауза, то аргумент ставится на вершине клаузы.  

4. Вторичные предикации (со словом *сам*, в депиктивных конструкциях и т.д.) размечаются как отдельные предикатно-аргументные конструкции.  

## Примеры разметки
*Где ГУМ?*    
**предикат**: где  
**аргументы**: ARG0 (ГУМ)   


Где в Москве найти чебуреки?   
**предикат**: найти.9   
**аргументы**: ARG1 (чебуреки), ARG2 (Где)

**предикат**: где.1  
**аргументы**: ARG0 (чебуреки)  
**модификаторы**: ADVMOD (в Москве)  

**предикат**: в.1  
**аргументы**: ARG0 (чебуреки), ARG1 (Москве)  