# PSEUDOCÓDIGOS DE MÉTODOS NUMÉRICOS PARA INTEGRACIÓN

🌀 1. MÉTODO DEL TRAPECIO  
ALGORITMO MetodoTrapecio  
    DEFINIR f(x), a, b, n  
    h ← (b - a) / n  
    suma ← f(a) + f(b)  

    PARA i ← 1 HASTA n - 1 HACER  
        x ← a + i * h  
        suma ← suma + 2 * f(x)  
    FIN PARA  

    resultado ← (h / 2) * suma  
    IMPRIMIR "Resultado:", resultado  
FIN ALGORITMO  

🌀 2. MÉTODO DE SIMPSON 1/3  
ALGORITMO MetodoSimpson13  
    DEFINIR f(x), a, b, n  

    SI n ES IMPAR ENTONCES  
        IMPRIMIR "n debe ser par"  
        SALIR  
    FIN SI  

    h ← (b - a) / n  
    suma ← f(a) + f(b)  

    PARA i ← 1 HASTA n - 1 HACER  
        x ← a + i * h  
        SI i ES PAR ENTONCES  
            suma ← suma + 2 * f(x)  
        SINO  
            suma ← suma + 4 * f(x)  
        FIN SI  
    FIN PARA  

    resultado ← (h / 3) * suma  
    IMPRIMIR "Resultado:", resultado  
FIN ALGORITMO  

🌀 3. MÉTODO DE SIMPSON 3/8  
ALGORITMO MetodoSimpson38  
    DEFINIR f(x), a, b, n  

    SI n MOD 3 ≠ 0 ENTONCES  
        IMPRIMIR "n debe ser múltiplo de 3"  
        SALIR  
    FIN SI  

    h ← (b - a) / n  
    suma ← f(a) + f(b)  

    PARA i ← 1 HASTA n - 1 HACER  
        x ← a + i * h  
        SI i MOD 3 = 0 ENTONCES  
            suma ← suma + 2 * f(x)  
        SINO  
            suma ← suma + 3 * f(x)  
        FIN SI  
    FIN PARA  

    resultado ← (3 * h / 8) * suma  
    IMPRIMIR "Resultado:", resultado  
FIN ALGORITMO  

🌀 4. MÉTODO DE CUADRATURA GAUSSIANA (2 PUNTOS)  
ALGORITMO MetodoCuadraturaGaussiana  
    DEFINIR f(x), a, b  

    x1 ← -√(1/3)  
    x2 ← √(1/3)  

    t1 ← ((b - a)/2) * x1 + (a + b)/2  
    t2 ← ((b - a)/2) * x2 + (a + b)/2  

    resultado ← ((b - a)/2) * (f(t1) + f(t2))  
    IMPRIMIR "Resultado:", resultado  
FIN ALGORITMO  
