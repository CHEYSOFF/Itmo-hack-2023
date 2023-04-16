# Itmo-hack-2023
Решение кейса по отслеживанию и обработке трафика приложения, разработанное командой "Пиксели" в рамках хакатона ВК образование х ОК х ИТМО 15-16 апреля 2023 года. Мы предоставляем набор инструментов, упрощающих поиск и выявление ошибок, связанных с потреблением трафика приложением.

# Какие виды запросов мы поддерживаем?
### OKhttp

### Exoplayer

### Jni

### Picasso

### retrofit

### WebView


# Какой UI мы предоставляем?
Полученные в ходе работы библиотеки данные об использовании трафика отправляются на backend, где хранятся в POSTGRES. Имеется web приложение для иллюстрации изменений характеристик запросов 

## Пример подключения:

```
PixelSDK.configure("172.0.0.0")
PixelSDK.getOkHttpClient()
PixelSDK.getPicassoClient()
PixelSDK.getWebViewClient()
```
