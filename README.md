# Beytas Poetry Database

A MySQL poetry database for Persian literature, developed for the **Beytas** project.

This database is based on the **Ganjoor** database and has been extended with additional poets, poems, metadata, and structural improvements.

## Features

* MySQL database ready for import
* Based on the Ganjoor open-source database
* Additional Persian poets and poems
* Database structure improvements
* Optimized for modern MySQL versions
* UTF-8 (utf8mb4) support

## Origin

This project is derived from the **Ganjoor** database, which is distributed under the **MIT License**.

The original Ganjoor project can be found at:

https://github.com/ganjoor/desktop

## Changes Made

Compared to the original Ganjoor database, this project includes:

* Additional poets
* Additional poems
* Database schema improvements
* New fields and structural modifications
* Data corrections and optimizations
* Compatibility improvements for MySQL

## Installation

Import the SQL file into your MySQL server:

```bash
mysql -u username -p database_name < beytas_beytas.sql
```

or use phpMyAdmin, MySQL Workbench, or any compatible database management tool.

## License

The original data is based on the Ganjoor project, which is licensed under the MIT License.

Additional modifications and extensions have been created for the Beytas project.

Please keep the original copyright and license notices when redistributing this database.

## About Beytas

Beytas is a Persian poetry platform that provides searching, reading, discovering, and exploring Persian poems and poets.

Website:
https://beytas.ir

## Credits

Special thanks to the Ganjoor project and all contributors who have helped preserve and digitize Persian literature.

---

Made with ❤️ for Persian Literature.
