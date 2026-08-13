# ML Advanced — School 21

Репозиторий с решениями заданий из блока ML Advanced. Внутри — ноутбуки с регуляризацией, подбором гиперпараметров, метриками, ансамблями и сборкой пайплайнов.

## Структура проекта

* `ex00/` — L1 и L2 регуляризация (Lasso, Ridge)
* `ex01/` — подбор гиперпараметров через `GridSearchCV`
* `ex02/` — расчет и анализ метрик (ROC-AUC, F1, Precision, Recall)
* `ex03/` — ансамблевые методы (Voting, Bagging, Boosting)
* `ex04/` — построение `Pipeline` и сохранение моделей (`joblib` / `pickle`)

## Требования и окружение

Проект завязан на конкретные версии библиотек (в частности `scikit-learn 0.23.1`), поэтому лучше запускать в отдельном conda-окружении.

```bash
# Создание и активация env
conda create -n ml_advanced python=3.8 -y
conda activate ml_advanced

# Установка пакетов
pip install scikit-learn==0.23.1 tqdm==4.46.1 pandas numpy joblib notebook
