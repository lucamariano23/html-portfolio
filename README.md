# html-portfolio
import mysql.connector

db= mysql.connector.connect(
    host="localhost"
    user="root",
    password="user22",
    port=3007
)

print(db)
