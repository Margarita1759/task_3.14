[< к содержанию](./readme.md)

## Прекращение слияния при конфликте

Прервать слияние в случае конфликта можно параметром *merge* с флагом *--abort*. Он позволяет остановить процесс слияния и вернуть состояние, с которого этот процесс был начат.

```bash=
git merge --abort
```

Также при конфликте слияния можно использовать параметр *reset*, чтобы восстановить конфликтующие файлы до стабильного состояния.

```bash=
git reset
```