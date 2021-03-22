import amino

client = amino.Client()
client.login(email='YOUR_EMAIL', password='YOUR_PASSWORD')

subclients = client.sub_clients()
for name, id in zip(subclients.name, subclients.comId):
    print(name, id) 
