# calculadora-infinitacontinuar_usando = "SIM"
#feita por adeilton lins de santana

while continuar_usando == "SIM":
  #Criando um menu de opções
  print("SELECIONE A OPERAÇÃO DESEJADA")
  print("1 para Adição")
  print("2 para Subtração")
  print("3 para Multiplicação")
  print("4 para Divisão")
  print("0 para sair ")
  # Interação com o usuário
  operacao = input("\nQual operação você deseja realizar? ")


  #Criando as operações e as apresentações de respostas

  #Adição
  if operacao == "1":
    a1 = float(input("\nDigite o primeiro valor: "))
    a2 = float(input("Digite o segundo valor: "))
    adicao = a1 + a2
    print("\nA soma entre",a1,"e",a2,"é:",adicao,"\n")
    print("*"*33,"\n")
    continuar_usando = input("Gostaria de fazer outra operação? ").upper()
    print("*"*33,"\n")

  #Subtração
  if operacao == "2":
    b1 = float(input("\nDigite o primeiro valor: "))
    b2 = float(input("Digite o segundo valor: "))
    subtracao = b1 - b2
    print("\nA subtração entre",b1,"e",b2,"é:",subtracao,"\n")
    print("*"*33,"\n")
    continuar_usando = input("Gostaria de fazer outra operação? ").upper()
    print("*"*33,"\n")

  #Multiplicação
  if operacao == "3":
    c1 = float(input("\nDigite o primeiro valor: "))
    c2 = float(input("Digite o segundo valor: "))
    multiplicacao = c1 * c2
    print("\nA multiplicação entre",c1,"e",c2,"é:",multiplicacao,"\n")
    print("*"*33,"\n")
    continuar_usando = input("Gostaria de fazer outra operação? ").upper()
    print("*"*33,"\n")

  #Divisão
  if operacao == "4":
    d1 = float(input("\nDigite o primeiro valor: "))
    d2 = float(input("Digite o segundo valor: "))
    while d2 == 0:                  #Garantindo que d2 não seja zero!!

      if operaçao =="0":
        d1=float(input('\nEssa opção não existe” e voltar ao menu de opções'))


      
      print("O segundo valor não pode ser zero!")
      d2 = float(input("\nDigite o segundo valor (diferente de zero): "))
    divisao = d1 / d2
    print("\nA divisão entre",d1,"e",d2,"é:",divisao,"\n")
    print("*"*33,"\n")
    continuar_usando = input("Gostaria de fazer outra operação? ").upper()
    print("*"*33,"\n")
