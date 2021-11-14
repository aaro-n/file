<?php
$settings = array (
  'db_host' => '数据库主机',
  'db_name' => '数据库',
  'db_user' => '用户',
  'db_pass' => '密码',
  'db_table_prefix' => 'chv_',
  'db_driver' => 'mysql',
  'db_pdo_attrs' => 
  array (
  ),
  'debug_level' => 1,
);

if ( isset( $_SERVER['HTTP_X_FORWARDED_FOR'] ) ) {
  $http_x_headers = explode( ',', $_SERVER['HTTP_X_FORWARDED_FOR'] );
  $_SERVER['REMOTE_ADDR'] = $http_x_headers[0];
};
