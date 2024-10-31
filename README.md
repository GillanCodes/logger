# Logger

A small script write in Typescript to better log your app !

---

You must have a config file liek .env with these following lines :

```properties
APP_NAME=My_app_name
LOG_PATH=c:/PATH/TO/STORE/MY/LOGS/
```

---
How to use ?

1. Import log.js / log.ts in your file
2. call `log("mesage", type)`

NB : type can be a string, a number of nothing

Type List : 
 - number : 0 | string : "info" | default
 - number : 1 | string : "success"
 - number : 2 | string : "warn"
 - number : 3 | string : "error"
 - number : 4 | string : "debug"

---

Made by GillanCodes with <3
