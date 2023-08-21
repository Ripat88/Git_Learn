# Краткая инфа по Git
###
[Вводные команды по работе с Git](https://habr.com/ru/companies/ruvds/articles/599929/) <br>
[Ознакомиться с более подробным руководством](https://git-scm.com/book/ru/v2/Введение-О-системе-контроля-версий)

## статусы файлов

```mermaid
graph TD;
A[untracked] -->|git add| B{staged};
B -->|git commit| C[tracked];
C -->|изменения| D[modified];
D -->|git add| B[staged];
```

