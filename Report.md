# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

19.05.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/Cryofbb/Netology_Java_1.1/issues/1
* https://github.com/Cryofbb/Netology_Java_1.1/issues/2
* https://github.com/Cryofbb/Netology_Java_1.1/issues/3

## Описание процесса тестирования

В качестве тестовых данных использовались данные валидных кредитных карт с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html:

#### Expected result: Result is OK
| VISA  |           MasterCard |        American Express (AMEX)|Discover|
| ------------- | ------------- |------------------------------|--------|
|4929462614131169|5518194129569856|370163774752891|6011692297036392|
|4532102791588711|5379326213973382|378241721048647|6011762993839322|
|4916511831229143691|5487714990871318|341030337699453|6011623700644219456|

|JCB|Diners Club - North America|Diners Club - Carte Blanche|Diners Club - International|
|---|---|---|---|
|3540192519832469|5407707055308504|30487471652076|36287373058172|
|3539050955322788|5483916158670572|30206734936732|36896071098346|
|3535805201236361542|5459531233130649|30121327151955|36766602832424|

|Maestro|Visa Electron|InstaPayment|
|---|---|---|
|5893027727898530|4508982364096907|6383660822211814|
|6763769302864396|4508562409091871|6397452639735431|
|6763436079759148|4175008990834560|6374402299532674|

Тестирование производилось в следующем окружении:
  
* IntelliJ IDEA 2021.1.1 (Ultimate Edition)
  Build #IU-211.7142.45, built on April 30, 2021
  
* Runtime version: 11.0.10+9-b1341.41 amd64
  VM: Dynamic Code Evolution 64-Bit Server VM by JetBrains s.r.o.
  
* Windows 10 10.0
  GC: G1 Young Generation, G1 Old Generation
  Memory: 2042M
  Cores: 8

