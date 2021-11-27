# bottel


import datetime
import time
import random
def wishme():
	while True:
		hour = int(datetime.datetime.now().hour)
		per = str(input())
		var = ['olá','Oi','Bro']
		var2 = ['Tudo']
		now = time.ctime()
		if per in ['Olá','Oi','Bro','Kmk','Olá SIIA','SIIA']:
			bot = ['oi','ola']
			print(random.choice(bot))
		elif per in ['Tudo Bem?','Estás nice?','Nice e ai?','Na Boa']:
			bot2 = ['tudo e ai ?','yeah.Novidades?','bem e você?','Nc e ai?']
			print( random.choice(bot2))
		elif per in ['Também']:
				bot6 = ['Que bom!','Ótimo']
				print(random.choice(bot6))
		elif per in ['Eu Não Estou Bem','Não Estou Bem']:
					bot8 = ['Porquê?, você está irritado?']
					print(random.choice(bot8))
		elif per in ['sim']:
			print('Então faça coisas que não o erritem')
		elif per in ['Não']:
			print('Está Bem')
		elif per in ['Novidades?','novidades?','Novas?']:
			bot3 = ['Tenho uma']
			print(random.choice(bot3))
		elif per in ['que horas são?','que dia é hoje']:
			print(now)
		elif per in ['Qual é?','Qual']:
					bot4 = ['junior começou a programar','A Ford lançou um novo carro']
					print(random.choice(bot4))
		elif per in ['Tchau','Até amanhã','Até Mais Logo']:
						bot7 = ['Tchau...','Até mais logo...']
						print(random.choice(bot7))
						break
		elif per in ['que carro?']:
					print('A nova Ford Mustang Shelby GT 500 edição especial')
		elif per in ['Qual é O seu Nome']:
						print('Meu nome é SIIA')
					
		elif per in ['Obrigado']:
						bot5 = ['De nada','Disponha']
						print(random.choice(bot5))
		elif per in ['Posso Dormir Agora?']:
			print('Sim. Acho que são horas  de dormir' if hour >= 0 and hour < 12 else 'Não.Acho que ainda é cedo')
		else:
				print('nao sei')
			
			
			
wishme()
			
	
		
	
	
	
