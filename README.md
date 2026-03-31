tarefas = []

while True:
    print("\n1 - Adicionar tarefa")
    print("2 - Ver tarefas")
    print("3 - Sair")

    opcao = input("Escolha: ")

    if opcao == "1":
        tarefa = input("Digite a tarefa: ")
        tarefas.append(tarefa)
    elif opcao == "2":
        for t in tarefas:
            print("-", t)
    elif opcao == "3":
        break
    else:
        print("Opção inválida")
