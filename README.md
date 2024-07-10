## "Список покупок" для iOS  
Мобильное приложение для составления списка покупок

## Установка  
Для запуска проекта необходимо установить [Cocoapods](https://cocoapods.org/)  

Приложение использует следующие библиотеки:  
- [SnapKit](https://github.com/SnapKit/SnapKit) - верстка кодом без использования сторибордов
- [SwiftLint](https://github.com/realm/SwiftLint) - автоматическая проверка кода для поддержания общепринятого стиля 
- [SwiftGen](https://github.com/SwiftGen/SwiftGen) - автоматическая генерация кода ресурсов проекта

Для установки подов необходимо зайти в корневую папку проекта и через терминал добавить Podfile  
- ``pod init``

``platform :ios, '13.0'

target 'YourAppTargetName' do
  use_frameworks!

  # Pods for YourAppTargetName
  pod 'SnapKit'
  pod 'SwiftLint'
  pod 'SwiftGen'
  
end``
