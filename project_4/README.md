# Проект 4. Booking reviews

## Оглавление  
[1. Описание проекта](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)

[2. Какой кейс решаем?](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0) 

[3. Краткая информация о данных](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0) 

[4. Этапы работы над проектом](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0) 

[5. Результат](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)
    
[6. Выводы](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0) 

### Описание проекта    
Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов нахождения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель играет нечестно, и его стоит проверить.

:arrow_up:[к оглавлению](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)


### Какой кейс решаем?    
Построение модели, которая предсказывает рейтинг отеля.

**Условия соревнования:**  
- Тестовая выборка представлена в LeaderBoard целиком
- Делаем реальный ML продукт, который потом сможет нормально работать на новых данных

**Метрика качества**     
- mean_absolute_percentage_error(MAPE) < 13.5%

**Что практикуем**  
Практикуем различные виды обработки данных, в том числе и различное кодирование призанков   
Учимся повышать точность прогнозов, которые делает модель, с помощью более тщательной подготовки данных.


### Краткая информация о данных
Таблицы с данными по оценке отелей 
  
:arrow_up:[к оглавлению](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)


### Этапы работы над проектом  
- Получение данных
- Обработка данных
- визуализация данных
- Обучение модели

:arrow_up:[к оглавлению](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)


### Результаты:  
MAPE < 13.3. Точность предсказания модели увеличилась

:arrow_up:[к оглавлению](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)


### Выводы:  
При правильной обработке информации, выявлению верных признаков, очистке от не нужной информациии, можно улучшить качество предсказания модели.
:arrow_up:[к оглавлению](https://github.com/Grichick/sf_data_science/tree/main/project_4#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)

