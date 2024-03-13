# calculo-de-pintura

larg = float(input("Digite a largura da parede: "))
alt = float(input("Digite a altura da parede: "))
area = larg * alt
print(' as dimensoes sao de {}x{} e sua area é de {}m2'.format(larg,alt,area))
tinta = area / 2
print('para pintar essa parede sera necessario {}L de tinta'.format(tinta))
