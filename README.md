# API-from-DB
Dynamically generate RESTful APIs from the contents of a database table. Provides JSON, XML, and HTML. Supports most popular databases.


_config

/*
Example. Dataset name is  required field.

$args = array( 
            'name' => null,
            'username' => 'root',
            'password' => 'root',
            'server' => 'localhost',
            'port' => 3306,
            'type' => 'mysql',
            'table_blacklist' => array(),
            'column_blacklist' => array(),
);

register_db_api( 'dataset-name', $args );

*/
