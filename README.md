# Коллаборации 
Здесь представлены наши материалы работы по проекту «Паттерны коллаборации в российском социологическом сообществе: структура научных школ и возможные точки роста». 
В дополнение к выполненным работам в рамках проекта была разработана специализированная программа для сбора и обработки библиографических данных на русском языке из электронной библиотеки eLibrary, которая представлена в данном репозитории. 

## Программа «Bib-eLib» для сбора и обработки библиографических данных на русском языке из электронной библиотеки eLibrary
Программа «Bib-eLib» позволяет осуществлять выгрузку массива данных о научных публикациях через API электронной библиотеки eLibrary, проводить их предварительную обработку, решать проблему дизамбигуации авторов публикаций, проводить анализ итогового массива данных и осуществлять их визуализацию и создавать сеть связей между научными публикациями и их авторами в формате для дальнейшей обработки в программе Pajek.

Программа написана на языке программирования Python и включает архив файлов формата Jupyter Notebook (.ipynb) размером 266 КБ. Подходит для реализации на Windows, MacOS, Linux на базе интегрированных с ОС графических пользовательских интерфейсов (GUI). 

### Описание файлов .ipynb-files:
* `"0. Выгрузка данных о статьях авторов.ipynb"` - В этом файле производится выгрузка данных о статьях конкретных авторов на eLibrary через сервис API Elibrary 011 (не используется напрямую в программе, но может быть полезным);
* `"1. Выгрузка данных по статьям.ipynb"` – Представленный здесь код используется для выгрузки данных о статьях через API Elibrary;
* `"2.1. Предобработка данных и получение идентифицирующих признаков.ipynb"` – В этом файле проводится предобработка данных, выгруженных на этапе 1, с точки зрения работы с именами авторов; 
* `2.2. Обработка аффилиаций.ipynb` – В этом файле проводится предобработка данных, выгруженных на этапе 1, с точки зрения работы с аффилиациями авторов; 
* `2.3. Пост-обработка_новых_ID.ipynb` – В этом файле проводится пост-бработка данных – создание новых универсальных ID авторов на основе почищенных имен авторов и аффилиаций; 
* `"3. Анализ данных и визуализация.ipynb"` – В этом файле анализируются предварительно собранные и обработанные файлы, а также создаются графики; 
* `"4. Создание сетевых файлов для Pajek.ipynb"` – В этом файле создаются сетевые файлы для работы с графами в формате Pajek.


----
# Collaboration
Here are our materials on the project 'Collaboration patterns in the Russian sociological community: the structure of scientific schools and their growth potential' are presented. 
In addition to the work performed within the framework of the project, a specialized program was developed for collecting and processing bibliographic data in Russian from the electronic library eLibrary, which is presented in this repository.

## "Bib-eLib" program for collecting and processing bibliographic data in Russian from the electronic library eLibrary
The Bib-eLib program allows you to upload an array of data on scientific publications through the API of the electronic library eLibrary, carry out their preliminary processing, solve the problem of disambiguation of authors of publications, analyze the final data array and visualize them, and create a network of links between scientific publications and their authors in a format for further processing in the Pajek program.

The program is written in the Python programming language and includes a 266 KB Jupyter Notebook (.ipynb) file archive. Suitable for implementation on Windows, MacOS, Linux based on OS-integrated graphical user interfaces (GUI).

### Description of .ipynb-files:
* `"0. Выгрузка данных о статьях авторов.ipynb"` - This file uploads data about articles by specific authors via the Elibrary 011 API service (is not used in the program, but can be useful);
* `"1. Выгрузка данных по статьям.ipynb"` – The code provided here can be used to upload article data via the Elibrary API;
* `"2.1. Предобработка данных и получение идентифицирующих признаков.ipynb"` – This file preprocesses the data uploaded in the step 1 in terms of working with the names of authors;
* `2.2. Обработка аффилиаций.ipynb`  – This file preprocesses the data uploaded in the step 1 in terms of working with the affiliations of authors;
* `2.3. Пост-обработка_новых_ID.ipynb` - In this file, post-processing of the data is carried out - the creation of new universal author IDs based on the preprocessed names of authors and affiliations;
* `"3. Анализ данных и визуализация.ipynb"` – This file analyses pre-collected and processed files and creates graphs;
* `"4. Создание сетевых файлов для Pajek.ipynb"` – This file creates network files for working with graphs in Pajek format.
----
