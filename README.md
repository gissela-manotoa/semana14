# semana14
tareasemana14
def calcular_descuento(monto_total, porcentaje_descuento=10):
    descuento = (monto_total * porcentaje_descuento) / 100
    return descuento

# Llamadas a la función
monto1 = 1000  # Ejemplo de monto total
monto2 = 2000  # Otro ejemplo de monto total
porcentaje = 15  # Ejemplo de porcentaje de descuento diferente

descuento1 = calcular_descuento(monto1)
descuento2 = calcular_descuento(monto2, porcentaje)

# Cálculo del monto final
monto_final1 = monto1 - descuento1
monto_final2 = monto2 - descuento2

# Mostrar resultados
print(f"Compra 1 -> Monto total: ${monto1}, Descuento: ${descuento1}, Monto final: ${monto_final1}")
print(f"Compra 2 -> Monto total: ${monto2}, Descuento ({porcentaje}%): ${descuento2}, Monto final: ${monto_final2}")
