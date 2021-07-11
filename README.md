# IOS-SwiftUI

<p align='center'>
This repository was written based on this books.
<p align='center'>
</p>

<p align='center'>
  
<a href="https://www.raywenderlich.com/books/swiftui-apprentice" target="_blank">
<img src="https://img.shields.io/badge/SwiftUI Apprentice-yellow"/>
  
<a href="https://www.raywenderlich.com/books/swiftui-by-tutorials" target="_blank">
<img src="https://img.shields.io/badge/SwiftUI by Tutorials-yellowgreen"/>
  
<p align='center'>
</p>

# SwiftUI Apprentice
## Table of Contents: Overview
| Section I: | HIITFit | 
| ------------- | ------------- | 
| Checking Your Tools | [detailed](https://github.com/egorskikh/IOS-SwiftUI#checking-your-tools) | 
| Planning a Paged App | [detailed](https://github.com/egorskikh/IOS-SwiftUI#planning-a-paged-app) |
| Prototyping the Main View | [detailed](-) | 
| Prototyping Supplementary Views  | [detailed](-) |
| Organizing Your App's Data | [detailed](-) | 
| Adding Functionality to Your App | [detailed](-) |
| Observing Objects  | [detailed](-) | 
| Saving Settings | [detailed](-) |
| Saving History Data | [detailed](-) | 
| Refining Your App | [detailed](-) |
| Understanding Property Wrappers | [detailed](-) | 
| Apple App Development Ecosystem | [detailed](-) |
  
| Section II: | Cards | 
| ------------- | ------------- | 
| Outlining a Photo Collage App | [detailed](-) | 
| Gestures | [detailed](-) |
| Structures, Classes & Protocols | [detailed](-) | 
| Adding Assets to Your App  | [detailed](-) |
| Organizing Your App's Data | [detailed](-) | 
| Interfacing With UIKit | [detailed](-) |
| Paths & Custom Shapes | [detailed](-) | 
| Saving Files | [detailed](-) |
| Delightful UX — Layout | [detailed](-) | 
| Delightful UX — Final Touches | [detailed](-) |

| Section III | RWFreeView | 
| ------------- | ------------- | 
| Lists & Navigation | [detailed](-) | 
| Just Enough Web Stuff | [detailed](-) |
| Downloading Data | [detailed](-) | 
| Implementing Filter Options | [detailed](-) |
| Widgets | [detailed](-) | 
  
  
  
# SwiftUI by Tutorials
## Table of Contents: Overview

| Section I: | Diving Into SwiftUI | 
| ------------- | ------------- | 
| Introduction | [detailed](-) | 
| Getting Started | [detailed](-) |
| Diving Deeper Into SwiftUI | [detailed](-) | 
| Testing & Debugging | [detailed](-) |

| Section II: | Building Blocks of SwiftUI | 
| ------------- | ------------- | 
| Intro to Controls: Text & Image | [detailed](-) | 
| Controls & User Input | [detailed](-) |
| Introducing Stacks & Containers | [detailed](-) | 

| Section III: | State & Data Flow | 
| ------------- | ------------- | 
| State & Data Flow — Part I | [detailed](-) | 
| State & Data Flow – Part II | [detailed](-) |
| More User Input & App Storage | [detailed](-) | 
| Gestures | [detailed](-) |
| Accessibility | [detailed](-) | 
  
| Section IV: | Navigation & Data Display | 
| ------------- | ------------- | 
| Navigation | [detailed](-) | 
| Lists | [detailed](-) |
| Grids| [detailed](-) | 
| Sheets & Alert Views | [detailed](-) |

| Section V: | UI Extensions | 
| ------------- | ------------- | 
| Drawing & Custom Graphics | [detailed](-) | 
| Animations & View Transitions | [detailed](-) |
| Complex Interfaces | [detailed](-) |

| Section VI: | SwiftUI for macOS | 
| ------------- | ------------- | 
| Building a Mac App | [detailed](-) | 
| Converting an iOS App to macOS | [detailed](-) |

<br> </br>

# SwiftUI Apprentice. Table of Contents: Extended
## **Checking Your Tools**
### Key points
- [implementation](https://github.com/egorskikh/IOS-SwiftUI/tree/main/Section%201.%20HIITFit/01-checking-your-tools)
- Окно Xcode имеет панели навигатора, редактора и инспекторов, панель инструментов и область отладки, а также огромное количество настроек.
- Вы можете установить некоторые сочетания клавиш для навигации в разделе «Настройки» в соответствии с инструкциями в этой книге.
- Проект шаблона определяет приложение, которое запускается с ContentView и отображает «Hello, world!» в текстовом представлении.
- Вы можете просматривать документацию по быстрой справке в инспекторе или с помощью сочетания клавиш. Или вы можете открыть окно документации разработчика.
- При создании нового файла представления SwiftUI присвойте ему то же имя, что и создаваемому в нем представлению.
- Автоматическое завершение, сопоставление разделителей, сворачивание кода и проверка орфографии в Xcode помогают избежать ошибок.
- Вы можете выбрать один из шрифтов и цветовых тем Xcode, изменить один или создать свой собственный.
- Вы можете запустить приложение на моделируемом устройстве или создать предварительный просмотр конкретных устройств.
- Вы должны добавить учетную запись Apple ID в настройках Xcode, чтобы запустить приложение на устройстве iOS.
- При первом запуске проекта на устройстве iOS Apple требует, чтобы вы выполнили несколько шагов «Доверие».
<br> </br>

# Planning a Paged App
### Key points
- [implementation](https://github.com/egorskikh/IOS-SwiftUI/tree/main/Section%201.%20HIITFit/02-planning-a-paged-app/HIITFit)
- Спланируйте свое приложение, указав, что увидит пользователь и что будет делать приложение.
- Создайте свое приложение с представлениями и вложенными представлениями, настроенными с помощью модификаторов.
- Холст и редактор кода всегда синхронизированы: изменения, которые вы вносите в один, также отражаются в другом.
- Размещение нескольких представлений по вертикали в VStack или по горизонтали в HStack.
- Инспектор атрибутов помогает вам изменять вид или предварительный просмотр.
- ForEach позволяет перебирать полуоткрытый диапазон чисел.
- TabView может вести себя как вкладка или как контроллер страницы.
- Вы можете предварительно просмотреть или просмотреть изображение в реальном времени на холсте.
  

# SwiftUI by Tutorials. Table of Contents: Extended
