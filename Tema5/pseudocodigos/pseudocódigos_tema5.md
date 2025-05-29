# PSEUDOCÓDIGOS DE MÉTODOS DE INTERPOLACIÓN Y REGRESIÓN

🌀 1. MÉTODO DE INTERPOLACIÓN LINEAL  
ALGORITMO MetodoInterpolacionLineal  
    ENTRADA: (x0, y0), (x1, y1), x  
    SI x0 = x1 ENTONCES  
        IMPRIMIR "Error: puntos iguales"  
        SALIR  
    FIN SI  
    y ← y0 + ((y1 - y0) / (x1 - x0)) * (x - x0)  
    IMPRIMIR "Interpolación lineal en x:", y  
FIN ALGORITMO  

🌀 2. MÉTODO DE INTERPOLACIÓN DE MÍNIMOS CUADRADOS  
ALGORITMO MetodoMinimosCuadrados  
    ENTRADA: datos (x[i], y[i]), i=1 a n  
    SUMA_X ← 0  
    SUMA_Y ← 0  
    SUMA_XY ← 0  
    SUMA_XX ← 0  
    PARA i ← 1 HASTA n HACER  
        SUMA_X ← SUMA_X + x[i]  
        SUMA_Y ← SUMA_Y + y[i]  
        SUMA_XY ← SUMA_XY + x[i] * y[i]  
        SUMA_XX ← SUMA_XX + x[i] * x[i]  
    FIN PARA  
    m ← (n * SUMA_XY - SUMA_X * SUMA_Y) / (n * SUMA_XX - SUMA_X * SUMA_X)  
    b ← (SUMA_Y - m * SUMA_X) / n  
    IMPRIMIR "Recta de ajuste: y =", m, "* x +", b  
FIN ALGORITMO  

🌀 3. MÉTODO DE INTERPOLACIÓN DE LAGRANGE  
ALGORITMO MetodoInterpolacionLagrange  
    ENTRADA: puntos (x[i], y[i]), i=1 a n, valor x  
    y ← 0  
    PARA i ← 1 HASTA n HACER  
        L ← 1  
        PARA j ← 1 HASTA n HACER  
            SI j ≠ i ENTONCES  
                L ← L * (x - x[j]) / (x[i] - x[j])  
            FIN SI  
        FIN PARA  
        y ← y + y[i] * L  
    FIN PARA  
    IMPRIMIR "Interpolación de Lagrange en x:", y  
FIN ALGORITMO  

🌀 4. MÉTODO DE INTERPOLACIÓN DE NEWTON  
ALGORITMO MetodoInterpolacionNewton  
    ENTRADA: puntos (x[i], y[i]), i=1 a n, valor x  
    CALCULAR tabla de diferencias divididas D  
    y ← y[1]  
    producto ← 1  
    PARA k ← 1 HASTA n - 1 HACER  
        producto ← producto * (x - x[k])  
        y ← y + D[1][k+1] * producto  
    FIN PARA  
    IMPRIMIR "Interpolación de Newton en x:", y  
FIN ALGORITMO  

🌀 5. MÉTODO DE CORRELACIÓN  
ALGORITMO MetodoCorrelacion  
    ENTRADA: datos (x[i], y[i]), i=1 a n  
    CALCULAR media_x, media_y  
    SUMA_NUM ← 0  
    SUMA_DEN_X ← 0  
    SUMA_DEN_Y ← 0  
    PARA i ← 1 HASTA n HACER  
        SUMA_NUM ← SUMA_NUM + (x[i] - media_x) * (y[i] - media_y)  
        SUMA_DEN_X ← SUMA_DEN_X + (x[i] - media_x)^2  
        SUMA_DEN_Y ← SUMA_DEN_Y + (y[i] - media_y)^2  
    FIN PARA  
    r ← SUMA_NUM / (sqrt(SUMA_DEN_X) * sqrt(SUMA_DEN_Y))  
    IMPRIMIR "Coeficiente de correlación r =", r  
FIN ALGORITMO  

🌀 6. MÉTODO DE REGRESIÓN LINEAL  
ALGORITMO MetodoRegresionLineal  
    ENTRADA: datos (x[i], y[i]), i=1 a n  
    CALCULAR pendiente m y ordenada b con mínimos cuadrados  
    IMPRIMIR "Ecuación de regresión: y =", m, "* x +", b  
FIN ALGORITMO  
