# "CARS" TABLE STRUCTURE

| FIELD              | TYPE        | ATTRIBUTES                       | INDEXES     |
| ------------------ | ----------- | -------------------------------- | ----------- |
| id                 | INT         | NOT NULL,UNSIGNED,AUTO INCREMENT | PRIMARY KEY |
| kilometers         | MEDIUMINT   | NOT NULL,UNSIGNED                |
| model              | VARCHAR(30) | NOT NULL                         |
| old incidents made | TINYINT     | NULL                             |
| cost at exit       | FLOAT(8,2)  | NOT NULL,UNSIGNED                |
| price              | FLOAT(7,2)  | NOT NULL,UNSIGNED                |
| country of origin  | CHAR(2)     | NOT NULL                         |
