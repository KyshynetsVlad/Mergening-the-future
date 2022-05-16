<img src="https://github.com/KyshynetsVlad/Mergening-the-future/blob/main/Game/Graphics/Logo_22.png" align="left" width="192px" height="192px"/>

<img align="left" width="0" height="192px" hspace="10"/>

> ![Typing SVG](https://readme-typing-svg.herokuapp.com?size=24&color=F7B100&lines=Mergening+the+future)
> 
> «Розробка 2D гри в жанрі ARPG» 
> 
> 

![Under Development](https://img.shields.io/badge/under-development-orange.svg)

Головне завдання «Mergining the Furure» розробити проектні рішення для того, щоб задовольнити користувача ігровим процесом. Тримати гравця в інтризі та дати йому справжній тест навичок та вмінь.


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
> В якості основного підходу до розробки було обрано візуальне програмування, або так зване «Блокове складання» – логічні конструкції, масиви, які потім конвертуються в JSON-файл з набором різних параметрів  та значень. Чому саме такий спосіб проектування? А все тому, що основним завданням стала можливість показати всі плюси та можливості візуального програмування, як інструменту для створення абсолютно будь-яких програм для різних завдань та платформи.


## Модель проектування

Для проекту була вибрана ітераційна модель патерна. Це поведінкова модель проектування, яка дає можливість послідовно оминати елементи складових об'єктів, не розкриваючи їх внутрішнього уявлення. Коли потрібно мати кілька варіантів обходу однієї структури даних, або потрібно мати єдиний інтерфейс обходу різних структур даних, ітератор дозволяє винести реалізацію різних варіантів обходу в підкласи. Це дозволить легко взаємо замінювати об'єкти ітераторів залежно від того, з якою структурою даних доводиться працювати.


## Механіки

В грі реалізовані наступні механіки: 
-	покращення характеристик головного героя;
-	зміна амуніції;
-	механіка бою з ворогами, методом вибору найкращого рішення в потрібний момент;
-	взаємодія з персонажами;
-	взаємодія з предметами;
-	зміна стилів бою з босами;
-	зміна геймплею в залежності від локації та ситуації; 
-	штучний інтелект зі своїми особливостями.


## Реалізація та взаємодія

Основні можливості та функції зображено на діаграмі прецедентів, див. рисунок 1.1.

<p align="center"><img src="https://github.com/KyshynetsVlad/Mergening-the-future/blob/main/Game/Precedents.jpg" width="720px" height="520px"/><p/>
<p align="center">Рисунок 1.1. – Діаграма прецедентів</p>

## Результат

В активному тестуванні перші прототипи альфа-версій гри на комп'ютерах та мобільних пристроях. Проект знаходиться в активній розробці та вдосконалені вже розроблених функцій та механік. В майбутньому планується подальший реліз та супровід гри.

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
    "folderProject": true,
    "orientation": "landscape",
    "packageName": "com.MtFuture",
    "pixelsRounding": true,
    "projectUuid": "16abee44-f9d2-4553-ba82-ce520f150cd7",
    "scaleMode": "nearest",
    "sizeOnStartupMode": "adaptWidth",
    "useExternalSourceFiles": false,
    "version": "0.1.1",
    "name": "Merging the future",
    "description": "",
    "author": "Retro Team",
    "windowWidth": 2160,
    "windowHeight": 1080,
    "latestCompilationDirectory": "C:\\Users\\1\\Documents\\GDevelop projects\\My project13",
    "maxFPS": 60,
    "minFPS": 30,
    "verticalSync": false,
    "platformSpecificAssets": {
    


Завантаження програми та налаштування екрану

"loadingScreen": {
      "backgroundColor": 0,
      "backgroundFadeInDuration": 0,
      "backgroundImageResourceName": "Preview.png",
      "gdevelopLogoStyle": "light",
      "logoAndProgressFadeInDuration": 0,
      "logoAndProgressLogoFadeInDelay": 0,
      "minDuration": 3,
      "progressBarColor": 16777215,
      "progressBarHeight": 20,
      "progressBarMaxWidth": 200,
      "progressBarMinWidth": 40,
      "progressBarWidthPercent": 30,
      "showGDevelopSplash": true,
      "showProgressBar": true
    },
    "authorIds": [],
    "categories": [],
    "playableDevices": [],
    "extensionProperties": [],
    "platforms": [
      {
        "name": "GDevelop JS platform"
      }
    ],
    "currentPlatform": "GDevelop JS platform"
  },
  "resources": {
    "resources": [
      {
        "alwaysLoaded": false,
        "file": "3.png",
        "kind": "image",
        "metadata": "",
        "name": "3.png",
        "smoothed": false,
        "userAdded": true
      },



Завантаження головного меню та налаштування кнопок і відображення

"objects": [],
  "objectsGroups": [],
  "variables": [],
  "layouts": [
    {
      "b": 209,
      "disableInputWhenNotFoc{
  "b": 209,
  "disableInputWhenNotFocused": true,
  "mangledName": "MainMenu",
  "name": "MainMenu",
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
    "gridColor": 14484255,
    "gridAlpha": 0.2,
    "snap": false,
    "zoomFactor": 0.3999999999999992,
    "windowMask": false
  },
  "objectsGroups": [],
  "variables": [],
  "instances": [
    {
      "angle": 0,
      "customSize": false,
      "height": 0,
      "layer": "",
      "locked": false,
      "name": "Start",
      "persistentUuid": "38b6d8fa-69a9-4cbd-b625-5542328d3650",
      "width": 0,
      "x": 735,
      "y": 410,
      "zOrder": 2,
      "numberProperties": [],
      "stringProperties": [],
      "initialVariables": []
    },
    {
      "angle": 0,
      "customSize": false,
      "height": 0,
      "layer": "HUD",
      "locked": false,
      "name": "Setting",
      "persistentUuid": "06ce5d1d-7845-4e69-9977-77ffc3510b99",
      "width": 0,
      "x": 808,
      "y": 540,
      "zOrder": 4,
      "numberProperties": [],
      "stringProperties": [],
      "initialVariables": []
    },
    {
      "angle": 0,
      "customSize": false,
      "height": 0,
      "layer": "",
      "locked": false,
      "name": "Credits",
      "persistentUuid": "f28e1621-fd96-4f64-91a0-b698e3bfe967",
      "width": 0,
      "x": 808,
      "y": 675,
      "zOrder": 5,
      "numberProperties": [],
      "stringProperties": [],
      "initialVariables": []
    },
```

## Завантажити додаток  

<p align="left">Версія для ПК ↓</p>

[<img src="https://github.com/KyshynetsVlad/Poltava/blob/main/Practic_Interface/download-1915749__480.png" width="64px" height="64px"/>](https://drive.google.com/file/d/1BTcEDI57w2S14CUZKbJemXUSoy4whjQO/view?usp=sharing)  
<p align="center"><img src="http://qrcoder.ru/code/?https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1ebO_ga0XP0hcY_Kn2MtscxgPi0UtPOzk%2Fview%3Fusp%3Dsharing&4&0"/></p>
<p align="center"><b>УВАГА!!!
 <br>Мобільна версія може працювати нестабільно, вона знаходиться в активному тестуванні!!!</b></p>
