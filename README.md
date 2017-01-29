Простой чувашско-русский словарь
============================

Создан с использованием [Yii 2](http://www.yiiframework.com/). Содержит 500 чувашских слов (корней), с переводом на русский, примерами применения и описанием суффиксов слов.

Структура базы данных
-------------------

```
    chuvash
        id			идентификатор чувашского слова
        term		чувашское слово
    russian
        id			идентификатор русского перевода
        term		русский перевод
    chv2rus
    	chv_id		идентификатор чувашского слова
    	rus_id		идентификатор русского перевода
    	examples	примеры применения слов
    transcription
    	id			идентификатор транскрипции чувашского слова
    	value		транскрипция чувашского слова
    	chv_id		идентификатор чувашского слова
```

[![Yii2](https://img.shields.io/badge/Powered_by-Yii_Framework-green.svg?style=flat)](http://www.yiiframework.com/)