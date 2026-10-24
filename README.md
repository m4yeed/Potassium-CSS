<h1 align="center">Potassium-CSS</h1>

<p align="center">
  Purple CSS theme for Potassium executor with a custom wallpaper, blur and dim.
</p>


## Features

- Purple tint over the whole interface (color is adjustable)
- Custom wallpaper
- Adjustable wallpaper blur and dim
- Purple text selection and scrollbar

## Installation

1. Download the CSS file from this repo (open it → **Download raw file**).
2. Open Potassium and paste the contents of the file into its custom CSS.
3. Replace the wallpaper link (see below) and save.

## Wallpaper

Find this line in the CSS:


background: url("PHOTO URL HERE") center 22% / cover no-repeat;


and replace `PHOTO URL HERE` with a **direct link** to your image (it must end with `.jpg` or `.png`). A link to a page with the image will not work.

## Customize

All settings are at the top of the file:

| Variable | What it does |
|---|---|
| `--wall-opacity` | wallpaper visibility |
| `--wall-bright` | wallpaper brightness (dim) |
| `--wall-blur` | wallpaper blur |
| `--tint-opacity` | color tint strength |
| `--tint-color` | tint color |

Only CSS is used, no JavaScript.

<details>
<summary>ru </summary> Русский</summary>

## Возможности

- Фиолетовый оттенок поверх всего интерфейса (цвет настраивается)
- Свои обои
- Настройка размытия и затемнения обоев
- Фиолетовое выделение текста и скроллбар

## Установка

1. Скачай CSS-файл из репозитория (открой его → **Download raw file**).
2. Открой Potassium и вставь содержимое файла в поле кастомного CSS.
3. Замени ссылку на обои (см. ниже) и сохрани.

## Обои

Найди в CSS эту строку:


background: url("PHOTO URL HERE") center 22% / cover no-repeat;


и замени `PHOTO URL HERE` на **прямую ссылку** на свою картинку (она должна заканчиваться на `.jpg` или `.png`). Ссылка на страницу с картинкой не сработает.

## Настройка

Все параметры в начале файла:

| Переменная | Что делает |
|---|---|
| `--wall-opacity` | видимость обоев |
| `--wall-bright` | яркость обоев
