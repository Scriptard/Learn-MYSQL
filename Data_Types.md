# Data types in MySQL
---
A Data type specifies the particular type of data like integer, floating points, Boolean, String etc. It also identifies the possible values for that type, the operatio that can be performed on that type and the way that values that are stored.

Data types that MySQL supports are :-

## **Numeric Data Type**
---
 Data Type Syntax       | Description                |
| :------------- | :---------------------- |
| INT | A normal -sized integer that can be signed or unsigned. If signed, the allowable rage is from -2147483648 to  2147483648. If unsigned then it allowable ane is from 0 to 4294967295  | 
| TINYINT  | A very small int that can be signed or unsigned You can specify a width of up to 4 digits. |
| SMALLINT  | A small integer that can be usigned or unsigned you can specify a width of up to 5 digits  |
| MEDIUMINT  | a mediun-sized integer that can be signed or ungigned. you can specify a width of upto 9 digits.
| BIGINT  | A latger integer that can be signed or unsigned you can specify a width of up to 20 digits.  |
|  FLOAT (m,d) | A floating point number that can be signed or unsigned. you can define the display length(m)and the number of decimal (d). This is not required and will default to 10,2 where 2 is the number of decimals and 10 is the total number of digits(including decimals) Decimal precision can go to 24 places for a float |
| DOUBLE (m,d) | A double precision floating- pointthat cannot be unsigned. Precision can go to 53 places for double. REAL is a synonym for double  | 
|  DECIMAL(m,d) | An unpacked floationg-point number that cannot be unsigned. In unpacked decimals , each decimal corresponds to one byte. Defining the display length(m) an the number of decimal (d) is required,NUMERIC is a synonym for decimal |
---


---
## **Date and Time Data Type**
---
|  Data Type Syntax       | Size Range                | Explanation   |
| :------------- | :---------------------- |:---------------------- |
| DATE  | Values range from 1000-01-01 to 9999-12-31  | Displayed as 'yyyy-mm-dd'  |
| DATETIME  | Values range from 1000-01-01 00:00:00 to 9999-12-31  23:59:59 .  | Displayed as 'yyyy-mm-dd hh:mm:ss'  | 
| TIMESTAMP | Values range from '1970-01-01 00:00:01' UTC to '2038-01-19 03:14:07' UTC | Displayed as 'YYYY-MM-DD HH-MM-SS'.
| TIME   | Values range from '-838:59:59' to '838:59:59' | Dispalyed as 'HH-MM-SS' |
| YEAR(2/4) | Year values as 2 digits or 4 digits | Default is 4 digits |
---

## **String Data Types**
---
| Data Type Syntax| Size            | Explanation   |
| :------------- | :---------------------- |:---------------------- |
| CHAR(size)     | Maximum size of 255 characters | Where size is the number of characters to store. FIxed-length strings.Space padded on right to equal size characters. |
| VARCHAR(size)  | Maximun size is of 255 characters | Where size is the number of character to store.Variable-length string |
| TINYTEXT(size) | Maximun size is of 255 characters  | Where size is the number of characters to store |
| TEXT(size)     | Maximun size is of 65,535 characters | Where size is the number of characters to store |
| MEDIUMTEXT(size) | Maximun size is of 16,777,215 characters | Where size is the number of characters to store |
| LONGTEXT(size)  |  Maximun size is of 4GB or 4294967295 characters |  Where size is the number of characters to store |
| BINARY(size)   |  Maximum size of 255 characters | Where size is the number of binary characters to store. Fixed length strings. Space padded on right to equal size characters |
| VARBINARY(size)| Maximum size of 255 characters | Where size is the number of character to store.Variable-length string |


---
Large Object Data  (LOB) Data Types
| Data Type Syntax | Maximun Size                 |
| :--------------- | :------------------------    |
| TINYBLOB         | Maximun size of 255 bytes.   |
| BLOB(size)       | Maximun size of 65,535 bytes |
| MEDIUMBLOB       | Maximun size of 16,777,215   |








