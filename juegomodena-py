import random

def lanzar_moneda():
    return random.choice(['cara', 'cruz'])

def lanzar_dado():
    return random.randint(1, 6)

def jugar():
    # Solicita al jugador que introduzca su apuesta
    apuesta = int(input("Introduce tu apuesta (más de 1000 monedas): "))
    if apuesta <= 1000:
        print("La apuesta debe ser mayor a 1000 monedas.")
        return

  # Lanza la monenda y el dado
    resultado_moneda = lanzar_moneda()
    resultado_dado = lanzar_dado()

  # Muestra los resultados
    print(f"Resultado de la moneda: {resultado_moneda}")
    print(f"Resultado del dado: {resultado_dado}")

    if resultado_moneda == 'cara' and resultado_dado % 2 == 0:
        ganancia = apuesta * 2
        print(f"¡Ganaste! Tu ganancia es de {ganancia} monedas.")
    else:
        print("Perdiste. Mejor suerte la próxima vez.")

# Inicia el juego
jugar()
