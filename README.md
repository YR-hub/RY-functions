def precio_con_iva(precio):
    iva = 0.21 # Porcentaje de IVA
    precio_con_iva = precio * (1 + iva) # Cálculo del precio con IVA incluido
    return precio_con_iva
