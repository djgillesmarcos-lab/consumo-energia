def calcular_consumo():
    print("=== Calculadora de Consumo Elétrico Inteligente ===")
    aparelho = input("Digite o nome do aparelho (ex.: Geladeira): ")
    potencia = float(input("Digite a potência em Watts (W): "))
    horas_dia = float(input("Digite o uso diário em horas: "))
    consumo_mensal = (potencia * horas_dia * 30) / 1000
    print(f"\nAparelho: {aparelho}")
    print(f"Consumo estimado: {consumo_mensal:.2f} kWh/mês")

if __name__ == "__main__":
    calcular_consumo()
