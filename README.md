# DDLM: Digital Design Lab Manual
    
## Исходные коды к главам книги      
**Цифровой синтез: практический курс / под общ. ред. А. Ю. Романова, Ю. В. Панчула. – М.: ДМК Пресс, 2020. – 556 с.
ISBN 978-5-97060-850-0**    
    
**Авторы**: Антонов А. А., Барабанов А. В., Данчек Ч. Т., [Жельнио С. Л.](https://github.com/zhelnio "zhelnio"), Иванец С. А., Кудрявцев И. А., [Панчул Ю. В.](https://github.com/yuri-panchul "yuri-panchul"), [Романов А. Ю.](https://github.com/RomeoMe5 "RomeoMe5"), Романова И. И., Телятников А. А., Шуплецов М. С.   

Книга представляет собой расширенный практический курс, ориентированный на язык Verilog и обеспечивающий возможность выполнения практических задач на дешевых отладочных платах. Этот практикум дополняет и объединяет теоретические курсы по цифровой логике, языкам описания аппаратуры, компьютерной архитектуре и микроархитектуре, а также подготавливает студентов к работе с промышленными процессорными ядрами, к созданию специализированных вычислителей (например, ускорителей нейросетей) и курсов VLSI по проектированию массовых микросхем
ASIC. Материал каждой главы можно изучать автономно. В конце глав приводятся вопросы и упражнения, позволяющие преподавателям встраивать
данный материал в любой учебный курс, а читателям книги – закрепить новые знания, самостоятельно выполнив предлагаемые задания.     
    
Издание предназначено для студентов технических вузов, разработчиков аппаратно-программных систем, а также специалистов в области прикладной математики, интересующихся алгоритмами САПР.
        
## Как работать с репозитарием
        
Репозитарий содержит исходные коды к каждому практическому примеры в книге и разбиты на главы.      
Все коды адаптированы под выполнение на дешевой плате [Terasic De10-lite](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=1021),     
![Плата Terasic De10-lite](https://github.com/RomeoMe5/DDLM/blob/master/img/de10-lite.png)      
но мы **приветствуем комиты портов под другие платы** [alt_boards](https://github.com/RomeoMe5/DDLM/tree/master/alt_boards "Альтернативные платы").         

![Структура репозитария](https://github.com/RomeoMe5/DDLM/blob/master/img/repo_tree.png)       
Каждая папка соответствует определенной практической работе и может содержать поддиректории doc, pkg, img, **src**.         
![Внутри каждой папки](https://github.com/RomeoMe5/DDLM/blob/master/img/repo_dir.png)      
Все они содержат полезные материалы к работе. Главной является папка src, где лежат примеры исходных кодов, которые разбираются в главах книги.     
![Внутри папки главы](https://github.com/RomeoMe5/DDLM/blob/master/img/repo_lab4_tree.png)      
Каждый пример содержит файл верхнего уровня иерархии        
![Файл верхнего уровня иерархии](https://github.com/RomeoMe5/DDLM/blob/master/img/repo_lab4_top_level_entity.png)       
и папки со скриптами для симуляции и синтеза проекта.       

Предполагается, что при прочтении книги вы готовите отчет по каждой главе.      
Вы читаете главу исполняя практические примеры приведенные в главе. А в отчете описываете ход выполнения работы. Если в главе есть дополнительные задания для самостоятельной работы, их надо выполнить и описать ход выполнения в отчете.  Исходные коды документируются. А все примеры выполняются на плате.           
Таким образом будет достигнут максимальный эффект от освоения книги.        
![Дополнительные задания](https://github.com/RomeoMe5/DDLM/blob/master/img/repo_dop_zad.png)
        
## Контакты для связи
Любые ошибки, неточности или исправления, а также предложения о сотрудничестве присылайте на почту [a.romanov@hse.ru](https://github.com/RomeoMe5 "Александр Романов").

