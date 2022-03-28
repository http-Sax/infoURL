import socket
from ip2geotools.databases.noncommercial import DbIpCity

url = input('Ingrese la URL: ')
ip = socket.gethostbyname(url)

response = DbIpCity.get(ip, api_key='free')

print('IP:',ip)
print('Ciudad:',response.city)
print('Region:',response.region)
print('Pais:',response.country)
