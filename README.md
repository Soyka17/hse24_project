# Индивидуальная часть проекта

Выбранный геном - [Trypanosoma theileri](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_002087225.1/) 

> _Видовой комплекс Trypanosoma theileri включает паразитов крупного рогатого скота , передаваемых в основном слепнями и [кровососками](https://ru.wikipedia.org/wiki/Кровососки)._ 
>
> _Trypanosoma theileri является распространенным во всем мире гемопаразитом, о котором сообщалось на американском континенте у различных видов, включая крупный рогатый скот, буйволов и летучих мышей. У крупного рогатого скота высокая заболеваемость T. theileri может быть опасной в сочетании с другими инфекциями или в стрессовых ситуациях_

Ход работы можно посмотреть [тут](https://colab.research.google.com/drive/1k5G9GmL0gzmnUuwsDX8LR5ABT_O31p7v?usp=sharing) и [тут](https://colab.research.google.com/drive/1DTn4ESRcJ1DcL-nImhDsqGUwJJnWyYS0?usp=sharing) 

Таблица семейство ген (подробно см family_genes.tsv)

```shell
!head family_genes.tsv

family	      gene	          coordinates
14-3-3	      TM35_000162190	321660-322419
14-3-3	      TM35_000064860	915358-916150
14-3-3	      TM35_000034290	859230-862977
14-3-3	      TM35_000061090	41301-41646
2-Hacid_dh    TM35_000011720	196443-197685
2-Hacid_dh    TM35_000014360	887044-888130
2-Hacid_dh    TM35_000014370	889237-890278
2-Hacid_dh_C  TM35_000011720	196443-197685
2-Hacid_dh_C  TM35_000014360	887044-888130
```

Таблица по структурам:

| Участок                      | Число квадруплексов | Доля квадруплексов | Число предсказаний Zhun | Доля предсказаний Zhun | Число предсказаний ZDNABERT | Доля предсказаний ZDNABERT |
|------------------------------|---------------------|--------------------|-------------------------|------------------------|-----------------------------|----------------------------|
| Exons                        | 260                 |        33,2%       | 9480                    |          58,1%         | 4686                        |            83,6%           |
| Introns                      | 614                 |        78,4%       | 13838                   |          85,4%         | 5390                        |            92,5%           |
| Promoters (1000 up from TSS) | 394                 |        50,3%       | 10593                   |          65,4%         | 4857                        |            83,4%           |
| Downstream (200 bp)          | 783                 |        100%        | 16202                   |          100%          | 5824                        |            100%            |
| Intergenic                   | 783                 |        100%        | 16202                   |          100%          | 5824                        |            100%            |
