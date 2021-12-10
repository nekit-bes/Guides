# CLion

Зарегистрируйся со школьной почты на **JetBrains ,** и получи годовую лицензию на все продукты

![Screen Shot 2021-12-10 at 12.46.31 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_12.46.31_PM.png)

 (P.S. Я верю ты разберёшься как; [help](https://github.com/daniiomir/faq_for_school_21#get_jetbrains))

**#Создание проекта**

1. Нажми "**New Project**"
    
    ![Screen Shot 2021-12-10 at 1.07.48 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_1.07.48_PM.png)
    
2. Если создаем исполняемы файл, то выбираем  **C Executable.** (подойдет для *ft_printf* и *get_next_line*)
Для *Libft* выбирай **C Library.**
Выбираем папку проекта и нажимаем "**Create**"
(Вроде как в школе нужно использовать С99 , но это не точно. По этому стандарт языка и тип библиотеки оставляем по умолчанию.)
    
    ![Screen Shot 2021-12-10 at 2.07.09 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_2.07.09_PM.png)
    
3. В "**Open project Wizard**" ничего не меняем и жмем "**ok".**
    
    ![Screen Shot 2021-12-10 at 2.14.10 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_2.14.10_PM.png)
    
4. Нажми `**Ctrl`** + **`R`** или зеленую кнопку play что бы скомпилировать проект  
    
    ![Screen Shot 2021-12-10 at 2.55.24 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_2.55.24_PM.png)
    
5.  Терминал тут
    
    ![Screen Shot 2021-12-10 at 2.56.43 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_2.56.43_PM.png)
    

**#Настройка табуляции**

По умолчанию, при нажатии клавиши **tab** вставляются четыре пробела. Меняем это поведение.

1. Нажми **`⌘`** + **`Б`** откроются настройки, перейди в раздел **Editor → Code Style → C/C++ → Tabs and Indents** , и поставь чекбокс **Use tab character**
    
    ![Screen Shot 2021-12-10 at 12.59.37 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_12.59.37_PM.png)
    

**#42 Header**

1. Грузим **42header.jar** [отсюда](https://github.com/xrseventy/42_header_for_clion/blob/master/42header.jar)
2. Нажми `**⌘`** + `**Б**`  откроются настройки, выбери **Plugins**.
    
    ![Screen Shot 2021-12-10 at 11.17.41 AM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_11.17.41_AM.png)
    
3. Выбираем **42header.jar**
    
    ![Screen Shot 2021-12-10 at 11.35.15 AM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_11.35.15_AM.png)
    
4. Перезапускаем IDE
    
    ![Screen Shot 2021-12-10 at 11.39.16 AM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_11.39.16_AM.png)
    
5. Шапка вставляется при нажатии **alt + cmd + A**
    
    ![Screen Shot 2021-12-10 at 12.20.34 PM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_12.20.34_PM.png)
    

**#Add GitHub**

1. Нажми `**⌘` + `Б`** откроются настройки, перейди в раздел **Version Control → GitHub**.
2. Нажми **+** .
    
    ![Screen Shot 2021-12-10 at 10.51.26 AM.png](CLion%20f2f1839a3d684df79e135b2a42024176/Screen_Shot_2021-12-10_at_10.51.26_AM.png)
    

**#info**

- В папке "**cmake-build-debug**" находится отладочная информация, туда не лезем.
- В **[CMakeLists.txt](https://www.jetbrains.com/help/clion/cmakelists-txt-file.html#cmakelist-template)** содержит набор директив и инструкций, описывающих исходные файлы проекта.
    - Переменная *`set()` отвечает за стандарт языка по умолчанию.*
    - `add_executable`  описывает то какие файлы будет включать проект при компиляции и как будет называться бинарный файл.
        
        ```c
        add_executable(libftprintf.a ft_printf.c ft_printf.h)
        ```
        
        Это нужно при компиляции через нажатие клавиш `**Ctrl`** + **`R`**  (зеленая кнопка play)
        
        При создании новых файлов, не забывайте ставить чекбокс **Add to targets**
        Что бы новый файл автоматически прописался в **add_executable**
        
    - Когда бутете пушить проект в школьный git, удалите папку **cmake-build-debug** и фаил  **CMakeLists.txt**
    - Но лучше прописать все ненужные файлы и папки в **gitignore**
        
        ```bash
        /cmake-build-debug
        /CMakeLists.txt
        out
        # IntellijIdea files
        *.iml
        .idea
        ```
