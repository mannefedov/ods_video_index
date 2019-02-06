# ods_video_index


**ods_video_index.csv** - табличка с информацией о видосах. Поля - 'id', 'title', 'publishedAt', 'description', 'youtube_id'. По id нужно обращаться в api, по youtube_id можно собрать ссылку на видео (https://www.youtube.com/watch?v={youtube_id})

**id2transcripts.pkl** - pickle словарь с транскриптами для видео в табличке. Ключ - youtube_id из таблицы. Транскрипт выглядит вот так - 
```
[{'duration': 5.141,
  'start': 4.609,
  'text': 'добрый день меня зовут алексей я являюсь'},
 {'duration': 4.53,
  'start': 7.83,
  'text': 'разработчиком минской группы разработки'},
 {'duration': 4.71,
  'start': 9.75,
```

Табличка с видео (будет пополняться) - <https://docs.google.com/spreadsheets/d/1c4IC9cPgQwg3zMdi9_grVg278cBAZyTST4YxcAQDuS0/edit?usp=sharing)>
