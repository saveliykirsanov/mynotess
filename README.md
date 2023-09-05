# mynotess

print(not(0))
print(not(1))

cursor.execute(f"SELECT * FROM users;")
all_users = {x["email"]: x for x in cursor.fetchall()}
