# scientific_work
X-ray images captioning


## 1. Shikha version
Started with EDA

### Model 1 GRU Inception
- [(на конфе выступал)](Shikha_version/EDA/Model_1_GRU_Inception/(на_конфе_выступал)_Inception_model_(find+imp+ind).ipynb)
    Здесь использовал модель InceptionV3. Генерировал репорт с помощью приведения трех столбцов к одной строке
- [Три выхода](Shikha_version/EDA/Model_1_GRU_Inception/Copy_of_Inception_model_(find+imp+ind)_separately.ipynb)
    Попробовал, но пока что не доделал. Надо правильно настроить выходы
- [InceptionV3_(find+imp+ind)](Shikha_version/EDA/Model_1_GRU_Inception/Inception_model_(find+imp+ind).ipynb)
    Модель как для конфы, но тут 4 метрики BLEU
- [InceptionV3_(find+imp+ind)_separately](Shikha_version/EDA/Model_1_GRU_Inception/Inception_model_(find+imp+ind)_separately.ipynb)    
    Так же как и в модели "Три выхода", но эту не запускал

### po otdeldonsti predict
- [Model_2_GRU_with_CheXNet_(findings)](Shikha_version/po_otdelnosti_predict/Model_2_GRU_with_CheXNet_(findings).ipynb)
    Модель для генерации findings. Нужно доделать код. В последний раз редактировал и работал с ним
- [Model_2_Data_preparation](Shikha_version/po_otdelnosti_predict/Model_2_Data_Preparation.ipynb)
    Здесь подготовил датасет [final.csv](Shikha_version/data/final.csv) в котором пара изображений на вход