### Versiyon Karsilastirmasi

Güncelleme gerekliligi, sistemdeki program versioynu ile repository'deki versiyonarin karsilastirilmasi ile tespit olunur. Bu islemi apt-get update komutu yapar. Tespit edilen gereklilikler bir index dosyasina girilir.

    // to make an index_file
    apt-get update

Güncelleme islemi index_file a göre *apt-get upgrade* komutu ile hallolur. 

    // to upgrade
    apt-get upgrade

NOT: indirilen update dosyalarine ***archive***; indirilen yere ***cache*** denir. 

![sys_update](../Images/sys_update.png)