# Решение кейса Talent Case Contest 2023 от Сбер

Подробную инструкцию запуска решения можно найти прямо в файле под названием `TalentCaseSber.ipynb`

Для решения необходимо установить и запустить следующие библиотеки:
1. [pymorphy2](https://pypi.org/project/pymorphy3/)
2. [pyenchant](https://pyenchant.github.io/pyenchant/install.html)
3. [gensim](https://pypi.org/project/gensim/) Однако ее полезность сравнительно невысока

Итоговую кластеризацию на обработанных текстовых данных можно найти в файлах: `kmeans_text_data.csv`, `kmeans_norm_data.csv`, `kmeans_unique_data.csv` 
Приятного просмотра решения!

В финальном решении использована "помощь" полностью размеченного датасета с целью точнее определить качество кластеризации. Размеченные данные находятся в файле `case_label.xlsx`

Команда "Слон в банке"
