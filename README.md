a=1
while a!=5:
	print(" |Menu:| ")
	print(" ---------------")
	print(" |1 - Cadastrar| \n |2 - Ler      | \n |3 - Deletar  | \n |4 - Atualizar| \n |5 - Sair     |")
	print(" ---------------")

	op=int(input(" • Escolha algum dos itens acima: "))
	if op==1:
		b=0
		while b==0:
			print(" •Menu de cadastro: ")
			name=str(input("Nome do usuário: "))
			sur=str(input("Sobrenome do usuário: "))
			age=int(input("Idade do usuário: "))
			em=str(input("E-mail do usuário: "))
			passw=int(input("Senha, em números: "))
			yn=int(input(" •Deseja concluir o cadastro? \n 1-Sim\n 2-Não\n"))
			if yn==1:
				b=1
			elif yn==2:
				b=0
	if op==2:
		print("Nome do usuário: ", name)
		print("Sobrenome do usuário: ", sur)
		print("Idade do usuário: ", age)
		print("E-mail do usuário: ", em)
		print("Senha do usuário: ", passw)

	if op==3:
		print(" \n 1 - Nome do usuário: ", name)
		print(" 2 - Sobrenome do usuário: ", sur)
		print(" 3 - Idade do usuário: ", age)
		print(" 4 - E-mail do usuário: ", em)
		print(" 5 - Senha do usuário: ", passw)
		print(" 6 - Apagar tudo", "\n")	
		delet = int(input("•Qual deles deseja deletar? "))
		if delet==1:
			name = ("")
		if delet==2:
			sur = ("")
		if delet==3:
			age = ("")
		if delet==4:
			em = ("")
		if delet==5:
			passw = ("")
		if delet==6:
			name = ("")
			sur = ("")
			age = ("")
			em = ("")
			passw = ("")
		print("===================")
		
	if op==4:
		print(" \n 1 - Nome do usuário: ", name)
		print(" 2 - Sobrenome do usuário: ", sur)
		print(" 3 - Idade do usuário: ", age)
		print(" 4 - E-mail do usuário: ", em)
		print(" 5 - Senha do usuário: ", passw, "\n")
		print(" 6 - Atualizar tudo")	
		att = int(input("•Qual deles deseja atualizar? "))
		if att==1:
			name = input("Escreva sua alteração: ")
		if att==2:
			sur = input("Escreva sua alteração: ") 
		if att==3:
			age = input("Escreva sua alteração: ")
		if att==4:
			em = input("Escreva sua alteração: ")
		if att==5:
			passw = input("Escreva sua alteração: ")
		if att==6:
			name = input("Escreva sua alteração: ")
			sur = input("Escreva sua alteração: ")
			age = input("Escreva sua alteração: ")
			em = input("Escreva sua alteração: ")
			passw = input("Escreva sua alteração: ")
		print("===================")
	
			
								
	if op==5:
		quit=int(input(" 1-Sair\n 2-Não sair \n"))
		if quit==1:
			a=5
		elif quit==2:
			a=1
