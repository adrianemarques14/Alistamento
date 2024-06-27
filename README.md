ano = int(input('Digite o ano do seu nascimneto: '))
if 2024 - ano < 18:
    print('Você ainda terá que se alistar no exército')
elif 2024 - ano == 18:
    print('É a hora de você se alistar no exército')
else:
    print('Já passou o momento do seu alistamento')
