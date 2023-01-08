# HPC-SamaraUniversity-Fall-2022
Настоящий курс по дисциплине "Высокопроизводительные вычисления" предназначен для студентов магистерской программы ПМИ Самарского университета, осенний семестр 2022.

Лектор: [Якимов Павел Юрьевич](https://ssau.ru/staff/222993132-yakimov-pavel-yurevich) - доцент кафедры суперкомьютеров и общей информатики, к.т.н.

При подготовке курса были использованы следующие материалы:
- [NVIDIA CUDA C++ Programming Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html)
- [CUDA C++ Best Practices Guide](https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/index.html)
- Материалы компании Applied Parallel Computing LLC
- Наработки автора

# Лекции

Здесь представлены слайды для презентаций, которые демонстрировались во время лекций:
- Lecture 1 (12.09.2022, 17:00): Introduction to CUDA (Part 1) ([слайды](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/files/9951766/en_Introduction.pdf), [запись](https://bbb.ssau.ru:8443/playback/presentation/2.3/7b855197043755138a8976fc3ec0076688d3e316-1662987558703))
- Lecture 2 (26.09.2022, 17:00): Introduction to CUDA (Part 2) ([запись](https://bbb.ssau.ru:8443/playback/presentation/2.3/7b855197043755138a8976fc3ec0076688d3e316-1664197156887))
- Lecture 3 (24.10.2022, 15:15): GPU memory ([слайды](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/files/9951687/en_Memory.pdf), [запись](https://bbb.ssau.ru:8443/playback/presentation/2.3/7b855197043755138a8976fc3ec0076688d3e316-1666609796677))
- Lecture 4 (07.11.2022, 17:00): GPU Libraries ([слайды](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/files/10056576/3_libraries.pdf)
, [запись](https://bbb.ssau.ru:8443/playback/presentation/2.3/7b855197043755138a8976fc3ec0076688d3e316-1667826043704))
- Lecture 5 (21.11.2022, 17:00): Thrust ([слайды](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/files/10058169/4_thrust.pdf)
, [запись](https://bbb.ssau.ru:8443/playback/presentation/2.3/7b855197043755138a8976fc3ec0076688d3e316-1669034952591))
- Lecture 6 (05.12.2022, 15:15): ([слайды](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/files/10257959/5_mpgu_compressed.pdf)
, [запись](https://bbb.ssau.ru:8443/playback/presentation/2.3/7b855197043755138a8976fc3ec0076688d3e316-1670239428160))
- Lecture 7 (19.12.2022, 17:00): [ссылка на подключение](https://bbb.ssau.ru/b/964-em4-g9g-jiu)


# Лабораторные работы

[Ссылка в Google Drive на таблицу с результатами по лабораторным работам](https://docs.google.com/spreadsheets/d/1Kp8EHr0HnTKdmAFspkasLmo9XwCChDYc7jAcR8aPMmA/edit?usp=sharing)

1. [Matrix Multiplication, 0 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/Lab0_MatMul.pdf)
2. [VectorSum.pdf, 1 point](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/Lab1_VectorSum.pdf)
3. [Bilateral Filtering, 2 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/bilateral.pdf)
4. [Bilinear Interpolation, 1 point](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/bilinear_interpolation.pdf)
5. [Genetic Algorithm, 3 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/genetic_algorithm.pdf)
6. [Harris Detector, 2 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/harris_algorithm.pdf)
7. [Substrings Search, 2 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/mass_search.pdf)
8. [Pi-value Calculation, 1 point](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/pi_monte_carlo.pdf)
9. [Ray Tracing, 4 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/ray_tracing.pdf)
10. [Salt and Pepper, 2 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/salt_and_pepper.pdf)
11. [Spectrogram, 2.5 points](https://github.com/PavelYakimov/Samara-University-HPC-Fall-2022/blob/main/spectrogram.pdf)
12. Compare Intel GPU vs Nvidia GPU (please, refer to the lecturer), 3 points
13. Custom Task, 1-9 points (depends on the complexity of the provided task)

# Сценарий проведения зачета

Зачет будет проходить **10.01.2023 в 10:00** с использоанием BBB и Zoom.

Вначале вам необходимо подключиться в BBB ([ссылка на подключение](https://bbb.ssau.ru/b/964-em4-g9g-jiu)). Там будет вся оперативная информация, там же появится ссылка на тест.

Зачет состоит из двух частей.

### Прохождение теста

Ссылка на тест будет предоставлена в самом начале зачета. Прохождение теста должно занять у вас не более 60 минут. Тест состоит из вопросов по материалам лекций + задачи в виде: “вот код, какой ответ?”. 
Настоятельно прошу максимально не пользоваться ничем, кроме того, что сами уже знаете.

Как только заканчиваете тест, пишите об этом в чате bbb.

### Собеседование

Собеседование будет проходить с каждым по отдельности. Очередность собеседуемых будет определяться в основном треде зачета или в соответствии с тем, как будут приходить результаты теста.

В целом необходим только микрофон. Но легче общаться всё-таки с включенной камерой.

Во время собеседования сначала разберем ответы на вопросы теста.
Потом посмотрим на лабораторные работы и обсудим некоторые моменты в коде. Без лабораторных работ оценка за зачет выставлена не будет!

### Список вопросов

В целом обсуждать будем всё то, что было в лекциях (смотри раздел лекции).
Вопросы следующие:
1. Введение в параллельные вычисления. Пути достижения параллелизма. Классификация компьютерных систем. Характеристики схем коммуникации в многопроцессорных вычислительных систем. Высокопроизводительный вычислительный кластер СГАУ.
2. Производительность и параллелизм. Эволюция GPGPU. SIMD и SIMT, аппаратная архитектура GPU NVIDIA. Комплекс программного обеспечения CUDA Toolkit.Модель программирования CUDA: Основные принципы. Взаимодействие процессора и GPU. CUDA Сетка.
3. Уровни памяти (обзор). Глобальная память.
4. CUDA. Регистры, локальная память.
5. CUDA. Общая память. Постоянная память. Текстурная память.
6. CUDA. Реализация стандартных алгоритмов на GPU: Умножение матриц. Редукция.
7. CURAND, CUBLAS, CUSPARSE, CUFFT.
8. GPU программирование с использованием Thrust. Линейные преобразования и функторы. Заполнители и кортежи. Производительность. Взаимодействие с CUDA / С. Прикладные библиотеки.
9. Multi-GPU. Способы организации работы на нескольких GPU.
