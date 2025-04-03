# BPM-188 / F1102T-Upper-Arm-Blood-Pressure-Monitor
F1102T https://www.jamrmed.com/products/f1102t-upper-arm-blood-pressure-monitor.html  
BPM-188 https://sbershop.ru/catalog/sberdevices_sberzdorove/tonometr_sberzdorove_avtomaticheskiy/

#     Примеры ответа тонометра
###  Коды ошибок :  
02.40.DD.0C.3C.FF.FF.FF.FF.00.00.00.00.02.00.00.00.AF (18) err 2    
02.40.DD.0C.3C.FF.FF.FF.FF.00.00.00.00.04.00.00.00.A9 (18) err 4 нет давления в манжете  
02.40.DD.0C.3C.FF.FF.FF.FF.00.00.00.00.05.00.00.00.A8 (18) err 5 пережата трубка  

### измерение завершено :  
02-40-DD-0F-1C-00-9E-00-4E-00-00-00-42-00-19-02-0B-17-0F-14 (20)  
  
02.40.DD - заголовок  
0F.1C - ОК  
00.9E - систолическое (158)  
00.4E - диастолическое (78)  
00.00 - ? (возможно индикатор аритмии, нужно подтверждение)  
00.42 - пульс (66)  
00 - пользователь (1)  
19.02.0B.17.0F.14  дата.время 25.02.11 23:15 02.11  (YY-MM-DD-hh-mm-ss)
