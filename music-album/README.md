# Определение жанра по изображению

## Задача проекта 
Необходимо разработать модель, которая определит жанр музыкального альбома по изображению его обложки.

## Данные
Изображения в формате PNG, упакованные в zip-архивы. Имя архива соответствует музыкальному жанру. Каждый zip-архив содержит папку с изображениями музыкальных обложек соответствующего жанра.

## Дополнительные задачи
Кластеризация: исследовать, какие жанры лучше выделяются на фоне других, а какие – трудноразделимы.
API MusicBrainz: расширение датасета новыми изображениями. Можно расширить список жанров и использовать обратную сторону обложки.
OCR + NLP: извлечь текст из изображения и обогатить решение применением NLP.
Создать рекомендательную систему в миниатюре, опираясь на изображения.
Streamlit оформить классификатор жанров или рекомендательную систему в виде веб-приложения.

## Стэк
numpy, pandas, seaborn, matplotlib, sklearn, torch, fastai

## Статус
Активно 