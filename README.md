# CDB
Php Costum Static PDO Db Class 

Install:
1-Define database variables first

DEFINE('DB_HOST','localhost');
DEFINE('DB_DB','database');
DEFINE('DB_USER','db_username');
DEFINE('DB_PASSWORD','db_password');

2-Add file "CDB.php" to working area
 include "CDB.php";
 
Usage:

Select command:
$users = DB::getall('SELECT * FROM users');
$user = DB::get('SELECT * FROM users WHERE id=?',array($id));
