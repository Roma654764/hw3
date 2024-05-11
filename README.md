pravilniy_parol = 'ukraine1'
sproba = 3

while sproba > 0:
    parol = input('Введіть пароль: ')
    if parol == pravilniy_parol:
        print('Пароль правильний, ласкаво просимо!')
        break
    else:
        sproba -= 1
        print(f'Неправильний пароль! Спробуй ще!')

if sproba == 0:
    print('Спроби Закінчились. Доступ заборонено.')
