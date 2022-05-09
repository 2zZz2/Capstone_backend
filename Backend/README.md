### Capstone database installation

1. ##### Install Packages

   Install AnvilL:

   ```
   pip install anvil-uplink
   ```
   
   Install PyMySQL:
   ```
   pip install PyMySQL
   ```
   
2. ##### Please refill the database connection infomation in the fourth block
   
   Fill in host, port, user, and password you create when creating the database; for example:
   ```
   def set_connection():
    db = pymysql.connect(host='localhost',
                         port = 3306, user='root', password='htdhylyzhh',
                         db='circle_database_version3')
    return db
   ```
   





 
