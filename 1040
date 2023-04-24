if __name__ == '__main__':
    n = input('Digite suas quatro notas separando-as por espaço: ').split()
    n1, n2, n3, n4 = float(n[0]), float(n[1]), float(n[2]), float(n[3])
    av1 = 2 * n1
    av2 = 3 * n2
    av3 = 4 * n3
    av4 = 1 * n4
    media = (av1 + av2 + av3 + av4) / 10
    print('Média: {:.1f}'.format(media))
    if media >= 7:
        print('Aluno aprovado. ')
    elif media < 5.0:
        print('Aluno reprovado. ')
    elif media >= 5.0 and media <= 6.9:
        print('Aluno em exame. ')
        e = float(input('digite nota de exame: '))
        print('Nota do exame: {:.1f}'.format(e))
        mf = (media + e) / 2
        if mf >= 5.0:
            print('Aluno aprovado. ')
        else:
            print('Aluno reprovado. ')
            print('Média final: {:.1f}'.format(mf))
