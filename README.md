[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9788460&assignment_repo_type=AssignmentRepo)
n = int(input("ingrese termino: "))

n1, n2 = 0, 1
cont = 0

if n <= 0:
   print("ingrese el numero :")
 
elif n == 1:
   print("secuencia ",n,":")
   print(n1)
# genera la secuencia
else:
   print("secuencia :")
   while cont < n:
       print(n1)
       p = n1 + n2
       
       n1 = n2
       n2 = p
       cont += 1
