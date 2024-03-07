# "CARS" TABLE STRUCTURE

| FIELD              | TYPE        | ATTRIBUTES                       | INDEXES     |
| ------------------ | ----------- | -------------------------------- | ----------- |
| id                 | INT         | NOT NULL,UNSIGNED,AUTO INCREMENT | PRIMARY KEY |
| kilometers         | MEDIUMINT   | NOT NULL,UNSIGNED                |
| model              | VARCHAR(30) | NOT NULL                         |
| old_incidents_made | TINYINT     | NULL                             |
| cost_at_exit       | FLOAT(8,2)  | NOT NULL,UNSIGNED                |
| price              | FLOAT(7,2)  | NOT NULL,UNSIGNED                |
| country_of_origin  | CHAR(2)     | NOT NULL                         |
