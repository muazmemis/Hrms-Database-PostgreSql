# hrmsDatabasePostgreSQL
Human Resources Management System - İnsan Kaynakları Yönetim Sistemi

- [FrontEnd-React](https://github.com/muazmemis/hrmsFrontEndReact)
- [BackEnd-Java](https://github.com/muazmemis/hrmsBackEndJava)
* * *

### <a href="hrmsPostgreSql.sql">Click</a> for database script codes.
* * *

### Tablo yapısı:
- <b>users</b> (<i>tüm kullanıcı türlerini saklayacağımız ana tablomuz</i>)
	- <b>candidates</b> (<i>iş arayan kullanıcılar</i>)
	- <b>employees</b>  (<i>sistem çalışanları</i>) 
	- <b>employers</b> (<i>iş veren kullanıcılar</i>)
	  - <b>employer_phones</b> (<i>iş verenlerin birden fazla telefonu olabileceği için ek bir tablo</i>)   
- <b>verification_codes</b> (<i>doğrulama sistemlerimiz için doğrulama kodlarını tutacağımız ana tablomuz</i>)
	- <b>verification_codes_candidates</b>  (<i>iş arayan kullanıcılar için kod ile doğrulama yapmak için tablomuz</i>)
	- <b>verification_codes_employers</b> (<i>iş veren kullanıcılar için kod ile doğrulama yapmak için tablomuz</i>)
- <b>employee_confirms</b> (<i>sistem çalışanlarının onaylama yapabilmesi için ana tablomuz</i>)
	- <b>employee_confirms_employers</b>  (<i>sistem çalışanlarının, iş verenlerini onaylayacağı tablo.</i>)
- <b>job_titles</b> (<i>iş pozisyonlarının isimlerini tutacağımız tablomuz.</i>)

* * *
### ER Diagram with DrawSQL
<p align="center"><img src="hrmsPostgreSql.png"></p>
