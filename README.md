Добавьте файлы с данными в папку notebooks\data, разархивировав их и сохранив архитектуру в раре.

Целевая папка - notebooks. В папках backend и frontend - в дальнейшем будет создано веб-приложение

Описание ноутбуков:
1_research - Общие исследования датасетов с самого начала, построения графиков и выявление корреляций

2_preprocessing - Основные функции и тест их работы по модулю математической статистики

3_tainring - Драфт-версия тренировки модели ансамблей, весь действительный код по тренировкам в файлах classif_train,
а по предсказаниям в classif_test

4_interface - В более общем виде использование инструментов пользователем, с настроенным вводом данных и их визуализацией и представлениями в 
человекочитаемом и машиночитаемом виде

5_test_research_and_report - Ноутбук с анализом новых тестовых данных. Ответ по аномалиям в конце ноутбука в виде отчета + инструмента с графиками

файлы hard_model.pkl и soft_model.pkl - файлы моделей ансамблей в формате пикл. Интерфейс взаимодействия к ним в ноутбуке classif_test