# hse21_hw2
HW2 Bioinformatics course


Вот ссылки на гугл-коллабы:
1) https://colab.research.google.com/drive/1KP87UPIz2Xz4411P6nmxTO7zHuYDSRTf?usp=sharing
   https://github.com/kseniashilova/hse21_hw2/blob/main/src/Shilova_Ksenia_HW2_ipynb_.ipynb
3) https://colab.research.google.com/drive/1UvV_rSIAQ0ZWOv1ZRMxHVarS7GV70wKM?usp=sharing
   https://github.com/kseniashilova/hse21_hw2/blob/main/src/Shilova_Ksenia_HW2_biopython_ipynb_.ipynb
  
Небольшая статистика:   
Всего белков было предсказано:  
![](https://github.com/kseniashilova/hse21_hw2/blob/main/images/all_amount.PNG)  
Cколько из них удалось аннотировать с помощью сравнения с бактерией MIL-1  (остались не аннотированы 3609 - 3331 = 278)
![](https://github.com/kseniashilova/hse21_hw2/blob/main/images/mil_1_amount.PNG)  
Cколько с помощью БД SwissProt  (остались не аннотированы 3609 - 52 = 3557)
![](https://github.com/kseniashilova/hse21_hw2/blob/main/images/swissProt_amount.PNG)  


Создание аннотированного генома бактерии в формате GenBank назодится во втором ноутбуке 

P.S. в файле GENOME.gbk я сделала поле productSwissProt для каждой последовательности (просто где-то это поле пустое), но те, где есть совпадения с белками, можно найти по ключевому слову E_value.


БОНУС
Я добавила файл в папку data GENOME_with_functions.gbk, где вместе с белками написаны и их функции (для SwissProt). Функции зафиксированы в поле function_SwissProt
