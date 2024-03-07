# "CARS" TABLE STRUCTURE

| FIELD              | TYPE        | ATTRIBUTES        | INDEXES |
| ------------------ | ----------- | ----------------- | ------- |
| id                 | INT         | NOT NULL,UNSIGNED |
| kilometers         | MEDIUMINT   | NOT NULL,UNSIGNED |
| model              | VARCHAR(30) | NOT NULL          |
| old incidents made | TINYINT     | NULL              |
| cost at exit       | MEDIUMINT   | NOT NULL,UNSIGNED |
| price              | SMALLINT    | NOT NULL,UNSIGNED |
| country of origin  | CHAR(2)     | NOT NULL          |
