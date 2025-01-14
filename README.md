# Факультатив "Компьютерное зрение"

**Описание:** Вы когда-нибудь задумывались, как роботы могут ориентироваться в пространстве и выполнять свои задачи, как поисковые системы могут индексировать миллиарды изображений и видео, как алгоритмы могут диагностировать медицинские изображения на предмет заболеваний, как автомобили с автоматическим управлением могут видеть и управлять автомобилем безопасно, или как Instagram создает фильтры?

В основе этих современных приложений ИИ лежат технологии компьютерного зрения, которые могут воспринимать, понимать и реконструировать сложный визуальный мир. Computer Vision – одна из самых быстрорастущих и захватывающих дисциплин искусственного интеллекта в современной академии и промышленности. Курс предназначен для того, чтобы познакомить студентов с постановками основных задач и основополагающих принципов на примерах частей реальных кейсов. В рамках программы будут рассмотрены классические подходы Computer Vison, знание которых является неотъемлемой частью и основой Computer Vision in Deep Learning.

**Продолжительность:** 1 семестр.

**Интенсивность занятий:** 2 пары в неделю.

**Содержание:** Классические методы обработки изображений, решение задач: классификации, распознавания и оценки параметров движения в видеопотоке.

**Что нужно знать и уметь:** владеть Python (numpy, matplotlib), элементы линейной алгебры, математического анализа, статистики.

Курс основан на материалах [CS131](https://github.com/StanfordVL/CS131_release)


# Программа курса:

0. [Вводное занятие:](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_00_introduction)
	- введение в область Computer vision;
	- основные задачи и направления.

1. [Формирование изображений. Основные понятия:](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_01_images)
    - представление изображений в компьютере;
    - работа с цветом;
    - аффинные преобразования;
    - знакомство с библиотеками cv2, skimage;
    - [домашнее задание](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_01_images/homework).


2. [Изображение в виде сигнала:](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_02_signals)
    - представление изображений в компьютере;
    - работа с цветом;
    - аффинные преобразования;
    - знакомство с библиотеками cv2, skimage;
    - [домашнее задание](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_02_signals/homework).


3. [Предобработка изображений:](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_03_processing):
   - гистограммы изображений;
   - цветовая коррекция;
   - пороговое выделение;
   - морфологические операции;
   - пирамиды изображений;
   - [домашнее задание](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_03_processing/homework).

4. [Глобальные признаки изображений](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_04_global_features):

- матрица смежности и текстурные признаки;
- выделение границ и контуров;
- контурные признаки;
- контураные признаки;
- [домашнее задание](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_04_global_features/homework).

5. [Глобальные признаки изображений](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_05_local_features):

- особые точки и их поиск;
- детекторы Харриса и Моравица;
- дескрипторы особых точек на примере SIFT;
- [домашнее задание](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_05_local_features/homework).


6. [Введние в ML](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_06_ml_intro):

- метрики;
- kNN;
- линейная модель для регрессии.


7. [Классификация](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_07_classification):

- метрики;
- kNN;
- SVM;
- логистическая регрессия;
- [домашнее задание](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_07_classification/homework).


8. [Кластеризация и сегментация на изображениях](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_08_segmentation):

- иерархическая кластеризация;
- mean-shift;
- метрики IoU/Dice;
- [домашнее задание](https://github.com/ml-dafe/cv_mipt_minor/tree/master/week_08_segmentation/homework).



## Перечень библиотек

Можно взять [`requirements.txt`](https://github.com/ml-dafe/cv_mipt_minor/blob/master/requirements.txt) из репозитория или установить следующие пакеты:

| **Requirements** |
| :-- |
| `jupyter`        |
| `matplotlib`     |
| `cv2 (4.2)`      | 
| `skimage`        |
| `numpy`          |
