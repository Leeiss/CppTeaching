    Дан файл с данными в формате csv. Сначала записано число записей - 1000
    Затем следует 1000 записей вида
    id,first_name,last_name,email,sex,ip_address,married,favorite_color,Shirt_size,Age
    создать структуру, поля которой будут содержать в себе данные строк 
    id              - uint
    first_name      - string
    last_name       - string
    email           - string
    sex             - bool
    ip_address      - string
    married         - bool
    favorite_color  - char[3]   (динамический массив)
    Shirt_size      - char[3]   (динамический массив)
    Age             - char[4]   (динамический массив)
    
    
    Необходимо:
    0. Из консоли задать имя файлов
    1. Считать данные из файла.csv
    2. Записать в бинарный файл. 
    3. Считать данные из только что записанного бинарного файла.
    4. Записать в новый файл1.csv (файл должен иметь идентичное содержание)
    
    * После каждого пункта не забывайте закрыть поток  
    * Обработать ошибку неверного ввода имен файла или считывание из поврежденного файла (повреждение записей, т.е. отсутствие некоторых полей DBdataBroken1.csv. Отсутствие некоторых записей целиком DBdataBroken2.csv)
        - Вывести ошибку на экран
        - При необходиости высвободить занятую память
    * переопределить для нее оператор << и >> для обычного и бинарного вывода.
    * красиво прописать конструкторы и деструкторы)

    В целом реализация чтения через методы FileReader не обязательна. Я лишь написал примерный план.  