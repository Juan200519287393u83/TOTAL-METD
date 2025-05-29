# PSEUDOCÓDIGOS DE MÉTODOS NUMÉRICOS PARA ENCONTRAR RAÍCES

🌀 1. MÉTODO DE LA SECANTE  
ALGORITMO MetodoSecante  
    DEFINIR f(x), x0, x1, tolerancia, max_iteraciones  

    PARA i ← 1 HASTA max_iteraciones HACER  
        f0 ← f(x0)  
        f1 ← f(x1)  
        x2 ← x1 - f1 * (x1 - x0) / (f1 - f0)  

        SI |x2 - x1| < tolerancia ENTONCES  
            IMPRIMIR "Raíz:", x2  
            SALIR  
        FIN SI  

        x0 ← x1  
        x1 ← x2  
    FIN PARA  

    IMPRIMIR "No se encontró raíz"  
FIN ALGORITMO  

🌀 2. MÉTODO DE BISECCIÓN  
ALGORITMO MetodoBiseccion  
    DEFINIR f(x), a, b, tolerancia, max_iteraciones  

    SI f(a) * f(b) ≥ 0 ENTONCES  
        IMPRIMIR "No hay cambio de signo"  
        SALIR  
    FIN SI  

    PARA i ← 1 HASTA max_iteraciones HACER  
        c ← (a + b) / 2  

        SI |f(c)| < tolerancia O (b - a)/2 < tolerancia ENTONCES  
            IMPRIMIR "Raíz:", c  
            SALIR  
        FIN SI  

        SI f(a) * f(c) < 0 ENTONCES  
            b ← c  
        SINO  
            a ← c  
        FIN SI  
    FIN PARA  

    IMPRIMIR "No se encontró raíz"  
FIN ALGORITMO  

🌀 3. MÉTODO DE LA FALSA POSICIÓN  
ALGORITMO MetodoFalsaPosicion  
    DEFINIR f(x), a, b, tolerancia, max_iteraciones  

    SI f(a) * f(b) ≥ 0 ENTONCES  
        IMPRIMIR "No hay cambio de signo"  
        SALIR  
    FIN SI  

    PARA i ← 1 HASTA max_iteraciones HACER  
        x ← b - f(b) * (b - a) / (f(b) - f(a))  

        SI |f(x)| < tolerancia ENTONCES  
            IMPRIMIR "Raíz:", x  
            SALIR  
        FIN SI  

        SI f(a) * f(x) < 0 ENTONCES  
            b ← x  
        SINO  
            a ← x  
        FIN SI  
    FIN PARA  

    IMPRIMIR "No se encontró raíz"  
FIN ALGORITMO  

🌀 4. MÉTODO DE NEWTON-RAPHSON  
ALGORITMO MetodoNewtonRaphson  
    DEFINIR f(x), f'(x), x0, tolerancia, max_iteraciones  

    PARA i ← 1 HASTA max_iteraciones HACER  
        fx ← f(x0)  
        dfx ← f'(x0)  

        SI dfx = 0 ENTONCES  
            IMPRIMIR "Derivada cero"  
            SALIR  
        FIN SI  

        x1 ← x0 - fx / dfx  

        SI |x1 - x0| < tolerancia ENTONCES  
            IMPRIMIR "Raíz:", x1  
            SALIR  
        FIN SI  

        x0 ← x1  
    FIN PARA  

    IMPRIMIR "No se encontró raíz"  
FIN ALGORITMO  
