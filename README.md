# Collaboration
Here are our materials on the project 'Collaboration patterns in the Russian sociological community: the structure of scientific schools and their growth potential'

## .ipynb-files:
* `"0. Выгрузка данных о статьях авторов.ipynb"` - В этом файле производится выгрузка данных о статьях конкретных авторов на eLibrary через сервис API Elibrary 011 / This file uploads data about articles by specific authors via the Elibrary 011 API service;
* `"1. Выгрузка данных по статьям.ipynb"` – Код, представленный здесь, можно использовать для выгрузки данных о статьях через API Elibrary / The code provided here can be used to upload article data via the Elibrary API;
* `"2. Предобработка данных и получение идентифицирующих признаков"` – В этом файле проводится предобработка данных, выгруженных на предыдущем этапе / This file preprocesses the data uploaded in the previous step;
* `"3. Анализ данных и визуализация.ipynb"` – В этом файле анализируются предварительно собранные и обработанные файлы, а также создаются графики / This file analyses pre-collected and processed files and creates graphs;
* `"4. Создание сетевых файлов для Pajek.ipynb"` – В этом файле создаются сетевые файлы для работы с графами в формате Pajek  / This file creates network files for working with graphs in Pajek format.

----

## Data scraping
- `GRANT_PARSING_v2_5_july_the_7th.ipynb` - ipynb-file with parcing of main dataset made by 7.07.2022 / файл, в котором происходит выгрузка данных по основному массиву от 7 июля 2022 года. 

- `GRANT_PARSING_authors_ids_5_10.ipynb` - ipynb-file with description of the process of getting ids of the articles of all the authors represented in our final data "FINAL_CORRECT_SOCIOLOGISTS.csv" / файл, в котором происходит выгрузка id статей всех авторов, представленных в нашем наборе даннных FINAL_CORRECT_SOCIOLOGISTS.csv.

## Data preparation
- `process_of_getting_only_russian_sociologists_74847_rows.ipynb` – ipynb-file with description of the process of combining a large dataframe and a dataframe with subsequent unloading and filtering of the dataframe only for Russian sociologists / файл, в котором производится объединение изначального датасета и выгруженного дополнительно в сентябре-октябре ('довыгрузка_социологов.csv').
- `Обработка_лаборатория_декабрь_2022_часть1.ipynb` - ipynb-file with description of data preparation (first names, last names and first and last names in english), part 1 / файл, в котором описан процесс обработки имен и фамилий авторов на русском и на английском, часть 1.
- `Обработка_лаборатория_декабрь_2022_часть2.ipynb` - ipynb-file with description of data preparation (first names, last names and first and last names in english), part 2 / файл, в котором описан процесс обработки имен и фамилий авторов на русском и на английском, часть 2.


## Data analysis
- `additional_papers_data_analysis_18_10_2022.ipynb` - ipynb-file with description of exploratory data analysis of additional dataframe with sociological (or not socilogical in some cases..) papers. We discussed it at the zoom-meeting 18.10.2022 (Darya, Tamara, Lika, Veneamin) / файл, в котором представлен эксплораторный анализ всех (включая дополнительно дособранные статьи) статей российских социологов.
- `Проект_коллаборации_апрель_анализ.ipynb` - ipynb-file with descriptive analysis of final dataset made in april 2023 / файл, в котором представлен дескриптивный анализ финального датасета, произведенный в апреле 2023 года.
