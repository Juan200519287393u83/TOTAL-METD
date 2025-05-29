# PSEUDOCÓDIGOS - Manejo de Errores Numéricos

🌀 1. OVERFLOW
ALGORITMO DetectarOverflow
    DEFINIR MAX_VALOR COMO el valor máximo permitido
    DEFINIR MIN_VALOR COMO el valor mínimo permitido

    ENTRADA numero

    SI numero > MAX_VALOR ENTONCES
        IMPRIMIR "¡Overflow positivo detectado!"
    SINO SI numero < MIN_VALOR ENTONCES
        IMPRIMIR "¡Overflow negativo detectado!"
    SINO
        IMPRIMIR "Número dentro del rango permitido"
    FIN SI
FIN ALGORITMO

🌀 2. REDONDEO
ALGORITMO RedondearNumero
    ENTRADA numero, decimales

    factor ← 10 ^ decimales
    resultado ← REDONDEAR(numero × factor) / factor

    IMPRIMIR "Número redondeado:", resultado
FIN ALGORITMO

🌀 3. TRUNCAMIENTO
ALGORITMO TruncarNumero
    ENTRADA numero, decimales

    factor ← 10 ^ decimales
    resultado ← TRUNCAR(numero × factor) / factor

    IMPRIMIR "Número truncado:", resultado
FIN ALGORITMO
