StepTracker



Приложение для просмотра фитнес активности пользователей



Использовалось: WPF, Newtonsoft.Json, паттерн MVVM.



Описание: Приложение десериализует JSON файлы с данными активности и на основе
этих данных в таблицу в главном окне выводятся данные о худшем, лучшем и среднем
результате по каждому пользователю. Также по каждому пользователю строится график
с количеством шагов по дням. Пользователи чьи лучшие и худшие результаты отличаются
от среднего более чем на 20% выделяются в таблице зеленным и красным цветом соответственно.
В приложении имеется экспорт данных по выбранному пользователю в файлы формата XML, JSON, CSV.
