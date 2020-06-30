<img src="https://raw.githubusercontent.com/yemrekeskin/pl-sql/master/ico.png" width="50" height="50">

# Querying , Data and Training Materials with PL/SQL

## Development Environment

- Oracle Server
  - 12**c** - 12 Cloud-Supported
  - 11g-12c-18c-19c
- IDE

  - SQL Developer
  - Toad For Oracle - En çok tercih edilen, daha profesyonel
  - PL/SQL Developer

  > **Toad For Oracle** ve **PL/SQL Developer** ide lerini kullanacaksanız **oracle client** veya **oracle odac** kurulması gerekiyor, Eğer **sqldeveloper** kullanacaksanız herhangi bir 3.parti program kurulmasına gerek yoktur,

## Installation and Configuration Steps

1. Administrator kullnıcısını aktif etmek

   - This PC > Manage > Local User and Groups > Groups > Adminstrators
   - Admin kullanıcısı ile giriş yapıp kurulum yapalım ya da **Run as Admin** diyerek kurmaya başlayalım

2. Oracle Server Kurulumu

   - Install Database Software Only
   - Authentication

3. Net Configuration Asistant

   - Listener Ayalarlama
   - Varolan veritabanını ağ ortamına açmak için kullanıyoruz
   - Add Listener > Port : 1521
   - Add Local Net Service > Service Name : orcl > Hostname : localhost/pcname/ip
   - Bir servis name içerisinden birden fazla veritabanı açılabilir,
   - Birden fazla servicename de açabilirsiniz

4. Database Congiguration Assistant

   - Database Create and Configuration
   - SID - System Identifier > ORCL
   - Character Set > Unicode
   - Sample Schema > HR - Human Resource
   - EM - Enterprise Manager > localhost:port/em/login > https://localhost:5500/em/login
   - Kullanıcılar
     - SYS - Sistemin tüm hakimiyeti, DBA olarak bağlanır(as sysdba), süper admin/user
     - SYSTEM - Bir şemadır, sadece SYSTEM şemasına hizmet eder, süper admin/user

## Links

- Oracle Server - https://www.oracle.com/downloads/
- Oracle PL/SQL Portal - https://www.oracle.com/database/technologies/appdev/plsql.html
- Oracle Database tools, libraries and SDKs - https://www.oracle.com/database/technologies/instant-client.html
- Sql Developer - https://www.oracle.com/tools/downloads/sqldev-downloads.html
- Toad® for Oracle - https://www.quest.com/products/toad-for-oracle/
- PL/SQL Developer - https://www.allroundautomations.com/products/pl-sql-developer/
