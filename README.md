Проект ментальной карты компании Константина. Для запуска потребуется установить obsidian (https://obsidian.md/download).

## Для того, чтобы открыть проект:
1) Скачиваем и устанавливаем Obsidian
2) Скачиваем проект. Понадобится git. Порядок команд git для терминала смотрите ниже
3) Открываем Obsidian. В окне выбора vault выбираем путь до скачанного репозитория в локальной файловой системе


## Примерный порядок команд git
### Вариант 1. Изначальный запуск
```bash
git clone git@github.com:RBizonDota/dnd_vault.git
```
### Вариант 2. Обновление
```bash
git checkout master
git pull
```
### Вариант 3. Загрузка обновления карты в репозиторий
```
git checkout -b <наименование новой ветки на англ. Должно отражать характер внесенных изменений>
git add .
git commit -m "<Прилагаемый комментарий к измененям>"
git push --set-upstream origin <наименование ветки>
<Далее идем в github и создаем pull request>
```

## Полезные ссылки
1) Obsidian https://obsidian.md/download
2) Гайд по obsidian https://www.youtube.com/watch?v=zYlDnmlo39Q
3) Гайд по git https://habr.com/ru/articles/541258/