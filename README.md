# websitecrf
## this website is my learning for python language.
## sharing knowledge for Linux system maybe others system.
## Mysql&mariadb database.
## you can visit this webpage at caoranfeng.com.
## database has a table named crf_users
create table crf_users(
user_id primary key auto_increment,
user_name not null,
user_passwd not null,
user_email char(50),
user_cellphone char(26),
regtime timestamp default now()
)


