# JSP-LogReg
Membuat Form Login dan Registrasi Dengan JSP

CREATE DATABASE jsp_logreg;

USE jsp_logreg;

CREATE TABLE  `admin` (
`id` INT( 5 ) NOT NULL AUTO_INCREMENT PRIMARY KEY ,
`username` VARCHAR( 25 ) NOT NULL ,
`password` VARCHAR( 25 ) NOT NULL ,
`email` VARCHAR( 25 ) NOT NULL ,
`regdate` DATE NOT NULL
) ENGINE = INNODB;
