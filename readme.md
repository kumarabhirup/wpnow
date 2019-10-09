# 🏄‍ wpnow

**⚡️ Easy WordPress boilerplate with now.sh workflow and documentation.**

## 🖥️ Spin up a WordPress Website

- Change the `easywp` alias to something different in `now.json` file.

- Set up a remote MySQL Database to get Database credentials.

- Run the following commands to spin up a WordPress instance.

```bash
$ git clone https://github.com/KumarAbhirup/wpnow <PROJECT_NAME>
$ cd <PROJECT_NAME>
$ npm i -g now

$ now secret add wordpress_db_name <MYSQL_DB_NAME>
$ now secret add wordpress_db_user <MYSQL_DB_USER>
$ now secret add wordpress_db_password <MYSQL_DB_PASSWORD>
$ now secret add wordpress_db_host <MYSQL_DB_HOST>
$ now secret add wordpress_salt <RANDOM SECRET STRING>

$ now # 🚀
```

> Note: You need a remote MySQL database to connect your WordPress to it. Look out for options online to host a MySQL database.
