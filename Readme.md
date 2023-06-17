# Лепендин Дмитрий | БПИ218 | ДЗ-8
компиляция:
```
gcc common.c writer.c -o writer -lpthread -lrt && gcc common.c reader.c -o reader -lpthread -lrt
```

Ввод - Терминал 1:
```
./writer
```
Ввод - Терминал 2:
```
./reader
```
