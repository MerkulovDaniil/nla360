---
title: 🏡 Main
listing:
  - id: team
    contents: 
      - team.yml
    template: team_listing_template.ejs
tbl-colwidths: [10,45,45]
---

# Вычислительная линейная алгебра

* Курс для 1-го курса бакалавриата ФПМИ МФТИ в рамках программы "AI360". 1 лекция + 1 семинар в неделю.
* Оценка за курс складывается из двух компонент в равном соотношении: 
  * Тесты, проводимые на семинарах.
  * Оценка за проект.

:::{.video}
pca_kittens.mp4
:::

|  №  | Лекция | Семинар |
|:-|:-----------------|:-----------------|
|  1  |  [Арифметика чисел с плавающей точкой. Векторные нормы. Устойчивость](lectures/lecture-1/lecture-1.ipynb)  | [Числа с плавающей точкой, основы линейной алгебры - векторы, матрицы](seminars/seminar-1/seminar-1.ipynb)<br>[🎥 Видео](https://youtu.be/X2ogSK0N9c0)<br>[💿 Скачать](https://disk.yandex.ru/i/lq9VeTZQML9sbQ) |
|  2  |  [Иерархия памяти, умножение матриц, алгоритм Штрассена](lectures/lecture-2/lecture-2.ipynb) |   [Нормы матриц, унитарные матрицы](seminars/2.pdf)<br>[✍️ Записи](notes/2.pdf)<br>[🎥 Видео](https://youtu.be/Bseq7NfsXV0)<br>[💿 Скачать](https://disk.yandex.ru/i/ckCwborduGIchA) |
|  3  | [Ранг матрицы, скелетное разложение, SVD](lectures/lecture-3/lecture-3.ipynb) |  [Ранг метрица, скелетное разложение, SVD, LoRA](seminars/3.pdf) <br>[✍️ Записи](notes/3.pdf)<br>[🎥 Видео](https://youtu.be/zTYHvfF54sY)<br>[💿 Скачать](https://disk.yandex.ru/i/diMn-tLq0Or3jw) |
|  4  | [Линейные системы](lectures/lecture-4/lecture-4.ipynb) | [SVD, PCA](seminars/4.pdf) <br>[👨‍💻 Eigenfaces](files/Eigenfaces_exercise.ipynb) <br>[✍️ Записи](notes/4.pdf)<br>[🎥 Видео](https://youtu.be/cAplBDXAGZc) <br>[💿 Скачать](https://disk.yandex.com/i/CdTTk2VOPI9R5A) |
|  5  | [Собственные значения и собственные векторы](lectures/lecture-5/lecture-5.ipynb)| [Линейные системы, Собственные значения и собственные векторы](seminars/5.pdf) <br>[✍️ Записи](notes/5.pdf)<br>[🎥 Видео](https://youtu.be/JM9ZGUMuuXo)<br>[💿 Скачать](https://disk.yandex.ru/i/kPRGCAL9g8dFXA) |
|  6  | [Обзор разложений матриц. Вычисление QR-разложения](lectures/lecture-6/lecture-6.ipynb) | [Процесс Грама-Шмидта + QR-разложение](seminars/6.pdf) <br> [✍️ Записи](notes/4.pdf)<br> [👨‍💻 Упражнение PageRank](https://colab.research.google.com/github/MerkulovDaniil/optim/blob/master/assets/Notebooks/PageRank_exercise_ru.ipynb) <br>[👨‍💻 Упражнение Modified Gram-Schmidt](https://colab.research.google.com/github/MerkulovDaniil/nla360/blob/master/files/qr_exercise.ipynb) <br>[🎥 Видео](https://youtu.be/rwGKZbKHs0M)<br>[💿 Скачать](https://disk.yandex.com/d/Q7g4RQSYDq6ZiA) |
|  7  |  [Проблема собственных значений симметричных матриц и SVD](lectures/lecture-7/lecture-7.ipynb)  | [Разложение Шура. QR-алгоритм и свойства его сходимости. Форма Гессенберга. Как вычислять сингулярные числа, если мы умеем вычислять собственные значения?](seminars/7.pdf) <br> [✍️ Записи](notes/7.pdf)<br> [👨‍💻 Упражнение на QR-алгоритм](https://colab.research.google.com/github/MerkulovDaniil/nla360/blob/main/files/qr_alg_exercise.ipynb) <br>[🎥 Видео](https://youtu.be/RAABMjfPOp8)<br>[💿 Скачать](https://disk.yandex.com/i/BXfh4JoHIz0VFA)  |
|  8  | [Рандомизированная линейная алгебра](lectures/lecture-8/lecture-8.ipynb) | [Рандомизированное SVD, рандомизированное умножение матриц](seminars/8.pdf) <br> [👨‍💻 Практика](https://colab.research.google.com/github/MerkulovDaniil/nla360/blob/main/files/randomized_la.ipynb) <br> [✍️ Записи](notes/8.pdf)<br> [🎥 Видео](https://youtu.be/dQcxBFwosrw)<br>[💿 Скачать](https://disk.yandex.ru/i/OAN1Vut_Y3sLzA) |
|  9  |   [От плотной к разреженной линейной алгебре](lectures/lecture-9/lecture-9.ipynb) |  [Практика с разреженными линейными матрицами](seminars/9.pdf) <br> [👨‍💻 Практика](https://colab.research.google.com/github/MerkulovDaniil/nla360/blob/main/files/sparse_la.ipynb) <br>[✍️ Записи](notes/9.pdf)<br> [🎥 Видео](https://youtu.be/WRLebviERb0)<br>[💿 Скачать](https://disk.yandex.ru/i/_qtMJo5ZmrWJjw) |
| 10  | [Прямые методы решения линейных систем](lectures/lecture-10/lecture-10.ipynb)  | [Градиентный спуск + многочлены Чебышёва](seminars/10.pdf) <br> [✍️ Записи](notes/10.pdf)<br> [🎥 Видео](https://youtu.be/NzqhUpcHx78)<br>[💿 Скачать](https://disk.yandex.ru/i/fECbElpR9N2iVA) |
| 11  | [Введение в итерационные методы: метрод Ричардсона, Чебышёва](lectures/lecture-11/lecture-11.ipynb) |   [Метод сопряженных градиентов и предобуславливатели](seminars/11.pdf) [👨‍💻 Упражнения на итерационные методы и предобуславливатели](https://colab.research.google.com/github/MerkulovDaniil/nla360/blob/main/files/cg_exercise.ipynb) <br> [✍️ Записи](notes/11.pdf)<br> [🎥 Видео](https://youtu.be/yQMcc_hqLGg)<br>[💿 Скачать](https://disk.yandex.ru/i/kIbyYF6YgbR9ug) |
| 12  |  [Продвинутые итерационные методы. Lanczos, Arnoldi, GMRES.](lectures/lecture-12/lecture-12.ipynb)   | [Структурированные матрицы, БПФ, свертки, матрицы Тёплица](seminars/12.pdf) <br> [👨‍💻 Введение в преобразование Фурье, быстрые матвеки на питоне](https://colab.research.google.com/github/MerkulovDaniil/nla360/blob/main/files/fourier.ipynb) <br> [✍️ Записи](notes/12.pdf)<br> [🎥 Видео](https://youtu.be/uNyHZKfJPhQ)<br>[💿 Скачать]() |

:::{.center}
:::{#team}
:::
:::