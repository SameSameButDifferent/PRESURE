# PRESSURE

#Calvin Leo Groenewald, Zahid Aasif Bockle, Daniel Jerome Mukuddem

lista=[]
for i in range (100,7,-1):
	if i%7==0:
		p=3/100*i
		newnum=i-p
		lista.append(newnum)
print(lista)
print(min(lista))
print(max(lista))
print(sum(lista))
lista.sort()
print(lista)
lista.reverse()
print(lista)
lista.remove(95.06)
print(lista)
lista.clear()
print(lista)

