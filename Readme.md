# Клавиатурный тренажер

Этот проект представляет собой клавиатурный тренажер, реализованный на Python с использованием библиотеки Pygame. Это простая игра, которая помогает пользователям повысить скорость и точность набора текста.

## Начало работы

Следуя этим инструкциям, вы получите копию проекта, которая будет запущена на вашем локальном компьютере для целей разработки и тестирования.

### Предварительные условия

В вашей системе должны быть установлены Python и Pygame.

### Запуск программы

Чтобы запустить программу предварительно скачайте библиотеку PyGame http://www.pygame.org/, перейдите в директорию, содержащую файл Project.py, и выполните следующую команду:

python3 Project.py

## Как играть

1. Нажмите на поле ввода, чтобы начать игру.
2. Введите предложение, которое появится на экране.
3. Игра рассчитает вашу скорость набора текста в символах в минуту и количество допущенных вами ошибок.
4. Вы можете перезапустить игру, нажав кнопку "Перезапустить".
5. Результаты сохраняются в файл Results.txt
6. Предложения для тренировки можно самостоятельно задать в файле sentences.txt (в одной строке - одно предложение) 

## Unit tests

Юнит тесты написаны для функции get_sentence, остальные методы либо связаны с графическим отоброжением, либо являются основными методами игры, которые не имеет смысла тестировать отдельно.
