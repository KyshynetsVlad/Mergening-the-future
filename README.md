<img src="https://github.com/KyshynetsVlad/Poltava/blob/main/APK/assets/LogoProject.png" align="left" width="192px" height="192px"/>

<img align="left" width="0" height="192px" hspace="10"/>

> Технологічна практика 
> 
> «Розробка і супроводження програмного продукту» 
> 
> на тему «Мобільний додаток»

![Under Development](https://img.shields.io/badge/under-development-orange.svg)

Завданням практики є розробка мобільного застосунку для дітей, який був би здатен заохотити їх до вивчення літератури та культури рідного краю.   


## Рушій

В ході виконання завдання було використано середовище розробки кросплатформних додатків GDevelop 5.  
Рушій має багату функціональність та розширену систему для інтеграції з веб-ресурсами, вбудований редактор спрайтів, також він пропонує потужний інструмент для створення звукового супроводу, просту систему анімації елементів.  
Основні переваги:
-	візуальне програмування (логічні конструкції);
-	потужний редактор візуальних ефектів;
-	зручний редактор спрайтів та текстур; 
-	легке налаштування колізій та анімацій;
-	легкий в освоєнні;
-	вихідний код в JSON;
-	кросплатформність.  

Його можна використовувати навіть тим, хто далекий від програмування та не має навичок в цій галузі. Головна відмінність серед аналогів – це проста система скриптингу, можна писати код на JS, або складати логічні конструкції візуальним програмуванням.


## Модель проектування

Для проекту була вибрана ітераційна модель патерна. Це поведінкова модель проектування, яка дає можливість послідовно оминати елементи складових об'єктів, не розкриваючи їх внутрішнього уявлення. Коли потрібно мати кілька варіантів обходу однієї структури даних, або потрібно мати єдиний інтерфейс обходу різних структур даних, ітератор дозволяє винести реалізацію різних варіантів обходу в підкласи. Це дозволить легко взаємо замінювати об'єкти ітераторів залежно від того, з якою структурою даних доводиться працювати.


## Архітектура системи

Щоб показати логіку та зв’язки між структурами програми, було створено діаграму класів, де представлені основні можливості та функції цього застосунку, яку зображено на рисунку 1.1

<p align="center"><img src="https://github.com/KyshynetsVlad/Poltava/blob/main/Practic_Interface/Классы.png" width="720px" height="520px"/><p/>
<p align="center">Рисунок 1.1. – Діаграма класів</p>


## Результат

Зауважень стосовно продукту у замовника не було. Всі поставлені вимоги були виконані та задовольняють всім критеріям, замовнику сподобався додаток, його можливості та функціональність системи. По домовленості було обговорено про подальшу розробку та оновлення додатку, супровід, кінцевий реліз і впровадження системи.

## Вихідні коди

```json
Початкові параметри додатку

{
  "firstLayout": "",
  "gdVersion": {
    "build": 99,
    "major": 4,
    "minor": 0,
    "revision": 0
  },
  "properties": {
    "adaptGameResolutionAtRuntime": true,
    "folderProject": false,
    "orientation": "portrait",
    "packageName": "com.poltavainf",
    "pixelsRounding": false,
    "projectUuid": "ebca1216-beb3-4a30-b84f-7ddd4ced2da4",
    "scaleMode": "linear",
    "sizeOnStartupMode": "adaptHeight",
    "useExternalSourceFiles": false,
    "version": "1.0.0",
    "name": "Проект",
    "author": "Kyshynets Vlad & Rak Denis",
    "windowWidth": 720,
    "windowHeight": 1280,
    "latestCompilationDirectory": "",
    "maxFPS": 60,
    "minFPS": 20,
    "verticalSync": false,
    

Завантаження програми та налаштування екрану

"loadingScreen": {
      "backgroundColor": 0,
      "backgroundFadeInDuration": 0.2,
      "backgroundImageResourceName": "",
      "gdevelopLogoStyle": "light",
      "logoAndProgressFadeInDuration": 0.2,
      "logoAndProgressLogoFadeInDelay": 0.2,
      "minDuration": 1.5,
      "progressBarColor": 16777215,
      "progressBarHeight": 20,
      "progressBarMaxWidth": 200,
      "progressBarMinWidth": 40,
      "progressBarWidthPercent": 30,
      "showGDevelopSplash": true,
      "showProgressBar": true
    }, 



Завантаження головного меню та налаштування кнопок і відображення

"objects": [],
  "objectsGroups": [],
  "variables": [],
  "layouts": [
    {
      "b": 209,
      "disableInputWhenNotFocused": true,
      "mangledName": "_1052_1077_1085_1102",
      "name": "Меню",
      "oglFOV": 90,
      "oglZFar": 500,
      "oglZNear": 1,
      "r": 209,
      "standardSortMethod": true,
      "stopSoundsOnStartup": true,
      "title": "",
      "v": 209,
      "uiSettings": {
        "grid": false,
        "gridType": "rectangular",
        "gridWidth": 32,
        "gridHeight": 32,
        "gridOffsetX": 0,
        "gridOffsetY": 0,
        "gridColor": 10401023,
        "gridAlpha": 0.8,
        "snap": false,
        "zoomFactor": 0.36999999999999994,
        "windowMask": false
      }, 
```

## Завантажити додаток  

[<img src="https://github.com/KyshynetsVlad/Poltava/blob/main/Practic_Interface/download-1915749__480.png" width="64px" height="64px"/>](https://drive.google.com/file/d/1SD6d-Ml3ZV9MV_HDaUsjxuhuMEfsy_4k/view?usp=sharing)  
<p align="center"><img src="http://qrcoder.ru/code/?https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1SD6d-Ml3ZV9MV_HDaUsjxuhuMEfsy_4k%2Fview%3Fusp%3Dsharing&4&0"/></p>
