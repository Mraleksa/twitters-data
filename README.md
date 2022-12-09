Файл nn це нейромережа. Вона бере дані з файлу total.csv. Там 68 тис твітів. 0 - це із проукртегами, а 1 - це із тегами #IStandWithPutin
Модель тренується і зберігається. 

Файл twitter завантажує модель і обходить весь датасет (скачаний звідси https://www.kaggle.com/datasets/bwandowando/ukraine-russian-crisis-twitter-dataset-1-2-m-rows)
і класифікує твіти, результат зберігається у файл twitter.csv (це дані для 2го графіку тут https://texty-twitter.glitch.me/)

Також внизу цього файлу окремо збирається статистика із кіглівського датасету в файл stats.csv (це дані для 1го графіку тут https://texty-twitter.glitch.me/)
