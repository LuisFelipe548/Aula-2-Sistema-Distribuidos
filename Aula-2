# Aula-2-Sistema-Distribuidos
Codigo para cliente.py

import sockt
client = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
client.connect(("localhost", 5000))
client.sen("Ola servidor! sou o cliente.".encode())
resposta = client.recv(1024).decode()
print("Resposta do servidor:", resposta)
client.close()
