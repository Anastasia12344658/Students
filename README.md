# Students
Начало работы
Создать базу данных students
create students
use students
создать таблицы adminUsers и studentRecords следующими запросами или с помощью приложенного файла .xlsx
create table studentRecords
(
Student_Id int primary key identity(1, 1),
Student_Name varchar(50),
Student_Surname varchar(50),
Student_GPA varchar(50),
Student_Major varchar(50),
Student_Login varchar(50),
Student_Password varchar(50),
)
insert into studentRecords values('John', 'Smith', '98', 'Economics', 'john', 'john')

create table adminUsers 
(
U_ID int primary key identity(1,1),
U_Login varchar(50),
U_Password varchar(50),
U_Type varchar(50)
)
insert into adminUsers values('admin', 'admin', 'Admin')
insert into adminUsers values('employee', 'employee', 'Employee')
