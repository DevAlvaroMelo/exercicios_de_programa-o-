# exercicios_de_programacao_calculadora_de_horario_para_dormir

1. Solicitar ao usuário que insira a hora atual no formato 24 horas.
2. Ler a hora atual e armazená-la em uma variável (por exemplo, "hora_atual").
3. Solicitar ao usuário que insira a quantidade de horas que deseja dormir.
4. Ler a quantidade de horas e armazená-la em uma variável (por exemplo, "horas_dormir").
5. Calcular o horário em que o usuário vai acordar:
   - hora_acordar = hora_atual + horas_dormir
6. Exibir o horário em que o usuário vai acordar.


hora_atual = int(input("Insira a hora atual (formato 24h): "))

horas_dormir = int(input("Insira a quantidade de horas que deseja dormir: "))

hora_acordar = (hora_atual + horas_dormir) % 24

print(f"Você irá acordar às {hora_acordar} horas.")

hora_atual = int(input("Insira a hora atual (formato 24h): "))

horas_dormir = int(input("Insira a quantidade de horas que deseja dormir: "))

hora_acordar = (hora_atual + horas_dormir) % 24

print(f"Você irá acordar às {hora_acordar} horas.")
