# PATIKA-DEV-SQL-ODEV8


Merhabalar,

test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

Kolay Gelsin.


CREATE TABLE employee (
	ID integer,
	name VARCHAR(50),
	birtday DATE,
	email VARCHAR(100)
);





insert into employee (id, name, birtday, email) values (1, 'Renault Huckfield', '1985-12-06', 'rhuckfield0@princeton.edu');
insert into employee (id, name, birtday, email) values (2, 'Angelika Copplestone', '2004-02-21', 'acopplestone1@dailymotion.com');
insert into employee (id, name, birtday, email) values (3, 'Cathryn Daelman', '1968-05-28', 'cdaelman2@reference.com');
insert into employee (id, name, birtday, email) values (4, 'Eugene Baglan', '2006-08-28', 'ebaglan3@fc2.com');
insert into employee (id, name, birtday, email) values (5, 'Janina Hoyles', '1969-05-03', 'jhoyles4@statcounter.com');
insert into employee (id, name, birtday, email) values (6, 'Carlynne Laybourn', '1957-09-28', 'claybourn5@admin.ch');
insert into employee (id, name, birtday, email) values (7, 'Yule Stealy', '1912-12-13', 'ystealy6@privacy.gov.au');
insert into employee (id, name, birtday, email) values (8, 'Christen Terram', '1921-11-17', 'cterram7@sun.com');
insert into employee (id, name, birtday, email) values (9, 'Cad Showen', '1991-11-08', 'cshowen8@forbes.com');
insert into employee (id, name, birtday, email) values (10, 'Ansel Lakenden', '2016-09-16', 'alakenden9@dion.ne.jp');
insert into employee (id, name, birtday, email) values (11, 'Fraser MacCracken', '1974-11-26', 'fmaccrackena@privacy.gov.au');
insert into employee (id, name, birtday, email) values (12, 'Lurette Spackman', '1945-07-25', 'lspackmanb@github.com');
insert into employee (id, name, birtday, email) values (13, 'Rachel Paynes', '2000-08-01', 'rpaynesc@tuttocitta.it');
insert into employee (id, name, birtday, email) values (14, 'Cathrin O''Concannon', '1998-01-15', 'coconcannond@sourceforge.net');
insert into employee (id, name, birtday, email) values (15, 'Goldie Llywarch', '1954-07-01', 'gllywarche@bravesites.com');
insert into employee (id, name, birtday, email) values (16, 'Karlotta Wolfit', '1990-07-28', 'kwolfitf@biblegateway.com');
insert into employee (id, name, birtday, email) values (17, 'Oren Newlyn', '2021-10-16', 'onewlyng@chicagotribune.com');
insert into employee (id, name, birtday, email) values (18, 'Nicol Haverson', '1983-05-06', 'nhaversonh@cloudflare.com');
insert into employee (id, name, birtday, email) values (19, 'Kylie Stares', '1929-04-16', 'kstaresi@tripod.com');
insert into employee (id, name, birtday, email) values (20, 'Consuela covino', '1951-08-13', 'ccovinoj@bbb.org');
insert into employee (id, name, birtday, email) values (21, 'Nowell Ahrendsen', '2003-05-25', 'nahrendsenk@phpbb.com');
insert into employee (id, name, birtday, email) values (22, 'Sherye Deppe', '1933-10-14', 'sdeppel@bloglines.com');
insert into employee (id, name, birtday, email) values (23, 'Vick Dennitts', '1925-02-24', 'vdennittsm@baidu.com');
insert into employee (id, name, birtday, email) values (24, 'Petr Tallman', '1982-12-17', 'ptallmann@yellowbook.com');
insert into employee (id, name, birtday, email) values (25, 'Tades Desporte', '1975-11-23', 'tdesporteo@nyu.edu');
insert into employee (id, name, birtday, email) values (26, 'Tracy Edwardes', '1984-10-21', 'tedwardesp@craigslist.org');
insert into employee (id, name, birtday, email) values (27, 'Clarence Whitington', '1991-08-15', 'cwhitingtonq@123-reg.co.uk');
insert into employee (id, name, birtday, email) values (28, 'Marita MacGebenay', '1978-04-28', 'mmacgebenayr@quantcast.com');
insert into employee (id, name, birtday, email) values (29, 'Lesli Yurevich', '2013-01-15', 'lyurevichs@berkeley.edu');
insert into employee (id, name, birtday, email) values (30, 'Guinevere Prigg', '1967-06-12', 'gpriggt@independent.co.uk');
insert into employee (id, name, birtday, email) values (31, 'Duncan Trenaman', '1986-07-26', 'dtrenamanu@craigslist.org');
insert into employee (id, name, birtday, email) values (32, 'Margarethe Joll', '2011-11-26', 'mjollv@arstechnica.com');
insert into employee (id, name, birtday, email) values (33, 'See Olligan', '1984-07-23', 'solliganw@oracle.com');
insert into employee (id, name, birtday, email) values (34, 'Ulrike Thompson', '1913-02-06', 'uthompsonx@pbs.org');
insert into employee (id, name, birtday, email) values (35, 'Bevin Doneld', '1944-01-19', 'bdoneldy@edublogs.org');
insert into employee (id, name, birtday, email) values (36, 'Lilla Burgin', '1939-09-17', 'lburginz@drupal.org');
insert into employee (id, name, birtday, email) values (37, 'Pepillo Klimochkin', '2007-12-29', 'pklimochkin10@yellowpages.com');
insert into employee (id, name, birtday, email) values (38, 'Emogene Sarginson', '1911-07-02', 'esarginson11@foxnews.com');
insert into employee (id, name, birtday, email) values (39, 'Bathsheba Dedney', '1916-01-25', 'bdedney12@nytimes.com');
insert into employee (id, name, birtday, email) values (40, 'Katleen Pawsey', '1919-10-17', 'kpawsey13@scribd.com');
insert into employee (id, name, birtday, email) values (41, 'Lauree Gravatt', '1911-01-29', 'lgravatt14@tinypic.com');
insert into employee (id, name, birtday, email) values (42, 'Amandi Habishaw', '1926-07-06', 'ahabishaw15@geocities.jp');
insert into employee (id, name, birtday, email) values (43, 'Marci Alpes', '1960-06-16', 'malpes16@desdev.cn');
insert into employee (id, name, birtday, email) values (44, 'Valene Wycliff', '2020-08-25', 'vwycliff17@opensource.org');
insert into employee (id, name, birtday, email) values (45, 'Nichol Ninnotti', '1929-06-01', 'nninnotti18@surveymonkey.com');
insert into employee (id, name, birtday, email) values (46, 'Laney Jenk', '1996-03-03', 'ljenk19@tmall.com');
insert into employee (id, name, birtday, email) values (47, 'Corena Elegood', '2005-04-25', 'celegood1a@discuz.net');
insert into employee (id, name, birtday, email) values (48, 'Gage Rosengren', '1997-10-11', 'grosengren1b@state.tx.us');
insert into employee (id, name, birtday, email) values (49, 'Gayla Towson', '1929-06-16', 'gtowson1c@nydailynews.com');
insert into employee (id, name, birtday, email) values (50, 'Teodoor Clayill', '1968-12-04', 'tclayill1d@mozilla.org');





UPDATE employee 
SET name = 'Ahmet Yılmaz',
    birtday = '1992-02-24',
	  email = 'ahmet@yılmaz.com'
WHERE id = 2;


UPDATE employee 
SET name = 'Ayşe Gündoğdu',
    birtday = '1988-05-28',
	  email = 'ayşe@gundogdu.com'
WHERE name LIKE 'Rena%';

UPDATE employee 
SET name = 'Tarık Sever',
    birtday = '1960-11-20',
	  email = 'Tarık@sever.com'
WHERE birtday < '1944-04-18';


UPDATE employee 
SET name = 'Elif Sönmez',
    birtday = '1997-11-20',
	  email = 'elif@sönmez.com'
WHERE birtday > '2003-04-18';

UPDATE employee 
SET name = 'Şengül Yaşar',
    birtday = '1990-11-20',
	  email = 'şengül@yaşar.com'
WHERE email = 'claybourn5@admin.ch' ;






DELETE FROM employee
WHERE id=5;

DELETE FROM employee
WHERE name= 'Tarık Sever';

DELETE FROM employee
WHERE birtday = '1990-11-20';

DELETE FROM employee
WHERE id=14;

DELETE FROM employee
WHERE name ='Şengül';

