# API-from-DB
Dynamically generate RESTful APIs from the contents of a database table. Provides JSON, XML, and HTML. Supports most popular databases.


_config<br>

/*
Example. Dataset name is  required field.<br>

$args = array( <br>
            'name' => null, <br>
            'username' => 'root',<br>
            'password' => 'root',<br>
            'server' => 'localhost',<br>
            'port' => 3306,<br>
            'type' => 'mysql',<br>
            'table_blacklist' => array(),<br>
            'column_blacklist' => array(),<br>
);<br>
<br>
register_db_api( 'dataset-name', $args );<br>

*/
