# sql-odev-8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
  CREATE TABLE employee (
  id INTEGER PRIMARY KEY,
  name VARCHAR(50) NOT NULL,
  birthday DATE,
  email VARCHAR(100)
  );
   
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Sherilyn Creffeild', '1983-02-02', 'screffeild0@msu.edu');
insert into employee (id, name, birthday, email) values (2, 'Mabelle Shevels', '1979-10-03', 'mshevels1@edublogs.org');
insert into employee (id, name, birthday, email) values (3, 'Adham Beynke', '1971-05-21', 'abeynke2@examiner.com');
insert into employee (id, name, birthday, email) values (4, 'Cole De L''Isle', '1990-06-04', 'cde3@constantcontact.com');
insert into employee (id, name, birthday, email) values (5, 'Keriann McTrustram', '1950-09-13', 'kmctrustram4@jalbum.net');
insert into employee (id, name, birthday, email) values (6, 'Collen Durek', null, null);
insert into employee (id, name, birthday, email) values (7, 'Randi Cartman', '1959-08-07', 'rcartman6@gnu.org');
insert into employee (id, name, birthday, email) values (8, 'Cassius Rabbet', '1954-12-21', 'crabbet7@squarespace.com');
insert into employee (id, name, birthday, email) values (9, 'Jacinta Redmell', '1979-05-19', 'jredmell8@cmu.edu');
insert into employee (id, name, birthday, email) values (10, 'Aurore Yearnes', '1997-01-17', 'ayearnes9@eepurl.com');
insert into employee (id, name, birthday, email) values (11, 'Bunni Andras', '1979-06-24', 'bandrasa@usda.gov');
insert into employee (id, name, birthday, email) values (12, 'David Scaddon', '1995-02-25', 'dscaddonb@seesaa.net');
insert into employee (id, name, birthday, email) values (13, 'Ferdinand Girk', null, null);
insert into employee (id, name, birthday, email) values (14, 'Lynn Benson', '1995-10-03', 'lbensond@netscape.com');
insert into employee (id, name, birthday, email) values (15, 'Forester Ellery', '1954-08-16', 'fellerye@shareasale.com');
insert into employee (id, name, birthday, email) values (16, 'Remy Haken', '1988-08-27', 'rhakenf@over-blog.com');
insert into employee (id, name, birthday, email) values (17, 'Cecelia Haste', '1987-03-08', 'chasteg@biblegateway.com');
insert into employee (id, name, birthday, email) values (18, 'Feodora McElwee', '1987-06-03', 'fmcelweeh@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (19, 'Uriah Smeaton', '1960-04-21', 'usmeatoni@printfriendly.com');
insert into employee (id, name, birthday, email) values (20, 'Rene Tranfield', '1956-05-02', 'rtranfieldj@arstechnica.com');
insert into employee (id, name, birthday, email) values (21, 'Bev Bergin', '1959-04-27', 'bbergink@columbia.edu');
insert into employee (id, name, birthday, email) values (22, 'Maximo Lisciandri', null, 'mlisciandril@sciencedirect.com');
insert into employee (id, name, birthday, email) values (23, 'Jacquetta Mc Caghan', '1960-04-19', 'jmcm@stanford.edu');
insert into employee (id, name, birthday, email) values (24, 'Reamonn Spinke', '1952-11-26', 'rspinken@time.com');
insert into employee (id, name, birthday, email) values (25, 'Josefa Shotton', null, 'jshottono@youtu.be');
insert into employee (id, name, birthday, email) values (26, 'Greg Genner', '1980-04-11', 'ggennerp@utexas.edu');
insert into employee (id, name, birthday, email) values (27, 'Raymund Francescozzi', '1969-05-26', 'rfrancescozziq@multiply.com');
insert into employee (id, name, birthday, email) values (28, 'Kurt McGuinness', null, 'kmcguinnessr@mlb.com');
insert into employee (id, name, birthday, email) values (29, 'Barret Lavarack', null, 'blavaracks@phpbb.com');
insert into employee (id, name, birthday, email) values (30, 'Wyatt Fairleigh', null, 'wfairleight@jalbum.net');
insert into employee (id, name, birthday, email) values (31, 'Tomaso Turri', '1962-08-10', 'tturriu@miitbeian.gov.cn');
insert into employee (id, name, birthday, email) values (32, 'Wayne Thor', '1950-11-01', 'wthorv@cisco.com');
insert into employee (id, name, birthday, email) values (33, 'Cordy Lovatt', '1978-01-08', 'clovattw@skyrock.com');
insert into employee (id, name, birthday, email) values (34, 'Ethyl Galler', '1995-02-27', 'egallerx@ebay.com');
insert into employee (id, name, birthday, email) values (35, 'Roxi Mairs', '1999-08-29', 'rmairsy@dell.com');
insert into employee (id, name, birthday, email) values (36, 'Irwin Battams', '1978-05-11', 'ibattamsz@thetimes.co.uk');
insert into employee (id, name, birthday, email) values (37, 'Osbourne Tinson', null, 'otinson10@miitbeian.gov.cn');
insert into employee (id, name, birthday, email) values (38, 'Vergil Mackett', null, 'vmackett11@behance.net');
insert into employee (id, name, birthday, email) values (39, 'Marve Klagges', null, 'mklagges12@bloglovin.com');
insert into employee (id, name, birthday, email) values (40, 'Kessia Matijasevic', '1964-07-18', 'kmatijasevic13@ask.com');
insert into employee (id, name, birthday, email) values (41, 'Akim Malkie', null, 'amalkie14@wordpress.org');
insert into employee (id, name, birthday, email) values (42, 'Ahmad Minards', null, 'aminards15@amazon.de');
insert into employee (id, name, birthday, email) values (43, 'Hew Wellstood', '1989-09-02', 'hwellstood16@microsoft.com');
insert into employee (id, name, birthday, email) values (44, 'Daven O''Keenan', '1993-06-02', 'dokeenan17@mac.com');
insert into employee (id, name, birthday, email) values (45, 'Stevie Marchington', '1986-09-14', 'smarchington18@google.com');
insert into employee (id, name, birthday, email) values (46, 'Gardener Rogerson', '2001-11-29', 'grogerson19@altervista.org');
insert into employee (id, name, birthday, email) values (47, 'Lukas Rimour', '1956-12-07', 'lrimour1a@studiopress.com');
insert into employee (id, name, birthday, email) values (48, 'Rosemonde Gostyke', '1965-05-31', null);
insert into employee (id, name, birthday, email) values (49, 'Alexi Scoines', '1986-08-30', 'ascoines1c@istockphoto.com');
insert into employee (id, name, birthday, email) values (50, 'Rurik Bapty', '1999-11-26', null);
   
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
  UPDATE employee
SET name = 'Mayak Ceri',
	birthday = '1991-06-10',
	email = 'engurbuz@gmail.com'
WHERE id=2;

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
  DELETE FROM employee
WHERE name = 'Rurik Bapty';
