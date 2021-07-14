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
| Prototyping the Main View | [detailed](https://github.com/egorskikh/IOS-SwiftUI#prototyping-the-main-view) | 
| Prototyping Supplementary Views  | [detailed](https://github.com/egorskikh/IOS-SwiftUI#prototyping-supplementary-views) |
| Organizing Your App's Data | [detailed](https://github.com/egorskikh/IOS-SwiftUI#organizing-your-apps-data) | 
| Adding Functionality to Your App | [detailed](https://github.com/egorskikh/IOS-SwiftUI#adding-functionality-to-your-app) |
| Observing Objects  | [detailed](https://github.com/egorskikh/IOS-SwiftUI#observing-objects) | 
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
  
<br> </br>

## Prototyping the Main View
### Key points
- [implementation](https://github.com/egorskikh/IOS-SwiftUI/tree/main/Section%201.%20HIITFit/03-prototyping-main-view/HIITFit)
- SwiftUI декларативен: просто объявляйте представления в том порядке, в котором вы хотите, чтобы они отображались.
- Создавайте отдельные представления для элементов вашего пользовательского интерфейса. Это упрощает чтение и сопровождение кода.
- Используйте соглашение SwiftUI о размещении каждого модификатора в отдельной строке. Это упрощает перемещение или удаление модификатора.
- Xcode и SwiftUI предоставляют автоматические предложения и значения по умолчанию, которые часто подходят вам.
- Позвольте Xcode помочь вам избежать ошибок: используйте меню Command для встраивания представления в стек или в замыкание if-else или извлеките представление во вложенное представление.
- Приложение **SF Symbols** предоставляет изображения значков, которые можно настроить как текст.
- **Previews** - это простой способ проверить, как ваш интерфейс выглядит для разных пользователей.
настройки.
- **Swift** - это строго типизированный язык программирования.
- **GeometryReader** позволяет вам устанавливать размеры вида относительно размеров экрана.

<br> </br>

## Prototyping Supplementary Views
### Key points
- [implementation](https://github.com/egorskikh/IOS-SwiftUI/tree/main/Section%201.%20HIITFit/04-prototyping-supplementary-views/HIITFit)
- Тип Date имеет множество встроенных свойств и методов. Вам необходимо настроить DateFormatter для создания значимого текста, который будет отображаться вашим пользователям.
- Используйте представление контейнера формы, чтобы быстро разложить данные таблицы.
- ForEach позволяет перебирать элементы коллекции.
- ZStack полезен для удержания видов в одном слое по центру, в то время как виды в другом слое смещаются к краям.
- Вы можете указать значения вертикального выравнивания для HStack, значения горизонтального выравнивания для VStack и комбинированные значения выравнивания для ZStack.
- Xcode помогает быстро и безопасно реорганизовать имя параметра.
- Изображение часто нуждается в тех же трех модификаторах. Вы можете создать собственный модификатор, чтобы не повторяться.
- Кнопка имеет метку и действие. Вы можете определить Button несколькими способами.

<br> </br>

## Organizing Your App's Data
### Key points
- [implementation](https://github.com/egorskikh/IOS-SwiftUI/tree/main/Section%201.%20HIITFit/05-organizing-your-apps-data/HIITFit)
- Чтобы использовать коллекцию в цикле ForEach, у нее должен быть способ однозначно идентифицировать каждый из ее элементов. Самый простой способ - сделать его совместимым с Identifiable и включить id: UUID в качестве свойства.
- Перечисление - это именованный тип, полезный для группировки связанных значений, поэтому компилятор может помочь вам избежать таких ошибок, как неправильное написание строки.
- Используйте директивы компилятора для создания данных для разработки только во время разработки, а не в окончательной версии вашего приложения.
- Предварительный просмотр содержимого - удобное место для хранения кода и данных, которые вы используете только во время разработки. Его содержимое не будет включено в окончательную версию вашего приложения.
- Локализуйте свое приложение, чтобы привлечь к нему более широкую аудиторию. Замените пользовательский текст экземплярами NSLocalizedString, создайте файл English Localizable.strings, а затем используйте его в качестве файла ресурсов справочного языка для добавления других языков.

<br> </br>

## Adding Functionality to Your App 
### Key points
- [implementation](https://github.com/egorskikh/IOS-SwiftUI/tree/main/Section%201.%20HIITFit/06-adding-functionality-to-your-app/HIITFit)
- Декларативная разработка приложений означает, что вы объявляете, как должны выглядеть представления в пользовательском интерфейсе, а также от того, от каких данных они зависят. Фреймворк SwiftUI заботится о создании представлений, когда они должны отображаться, и обновлении их при каждом изменении данных, от которых они зависят.
- Доступ к данным = зависимость: чтение части данных в вашем представлении создает зависимость для этих данных в этом представлении.
- Единый источник истины: каждая часть данных имеет источник истины, внутренний или внешний. Независимо от того, где находится источник правды, у вас всегда должен быть единственный источник правды.
- Оболочки свойств дополняют поведение свойств: **@State**, **@Binding** и **@EnvironmentObject** объявляют зависимость представления от данных, представленных свойством.
- **@Binding** объявляет зависимость от свойства **@State**, принадлежащего другому представлению. **@EnvironmentObject** объявляет зависимость от некоторых общих данных, таких как ссылочный тип, соответствующий **ObservableObject**.
- Используйте логические свойства **@State** для отображения и скрытия модальных листов или подпредставлений. Используйте **@Environment** (\. PresentationMode) как еще один способ закрыть модальный лист.

<br> </br>

## Observing Objects
### Key points
- [implementation](https://github.com/egorskikh/IOS-SwiftUI/tree/main/Section%201.%20HIITFit/07-observing-objects/HIITFit)
- Создайте таймер, подписавшись на издателя таймера, созданного **Timer.publish(every:tolerance:on:in:options:)**.
- **@Binding** объявляет зависимость от переменной **@State**, принадлежащей другому представлению. @EnvironmentObject объявляет зависимость от некоторых общих данных, таких как ссылочный тип, соответствующий **ObservableObject**.
- Используйте **ObservableObject** как **@EnvironmentObject**, чтобы позволить подпредставлениям получать доступ к данным без необходимости передавать параметры.

<br> </br>

## Saving Settings
### Key points

<br> </br>

## Saving History Data
### Key points

<br> </br>

## Refining Your App 
### Key points

<br> </br>

## Understanding Property Wrappers 
### Key points

<br> </br>

## Apple App Development Ecosystem 
### Key points

<br> </br>


# SwiftUI by Tutorials. Table of Contents: Extended
