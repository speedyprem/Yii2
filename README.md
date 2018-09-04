#User Table Database Schema For Yii2 Starter Kit

Download complete source code from : https://www.freewebmentor.com/demos/

#User table structure

```
	CREATE TABLE IF NOT EXISTS `user` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `username` varchar(255) NOT NULL,
  `auth_key` varchar(32) NOT NULL,
  `password_hash` varchar(255) NOT NULL,
  `password_reset_token` varchar(255) NOT NULL,
  `email` varchar(100) NOT NULL,
  `status` smallint(10) NOT NULL,
  `role` int(11) NOT NULL,
  `created_at` int(11) NOT NULL,
  `updated_at` int(11) NOT NULL,
  PRIMARY KEY (`id`)
);

```

![Yii2 User Table schema](http://www.freewebmentor.com/wp-content/uploads/2016/07/yii2-user-table-schema.png "Yii2 User Table schema")


* You can download SQL table with admin login details from http://www.freewebmentor.com/2016/07/sql-user-table-schema-yii2-starter-kit.html
