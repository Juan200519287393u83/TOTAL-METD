# PSEUDOCÓDIGOS DE MÉTODOS NUMÉRICOS PARA ECUACIONES DIFERENCIALES

🌀 1. MÉTODO DE EULER  
ALGORITMO MetodoEuler  
    ENTRADA: función f(t, y), intervalo [t0, tf], valor inicial y0, paso h  

    t ← t0  
    y ← y0  

    MIENTRAS t ≤ tf HACER  
        IMPRIMIR "t =", t, "y =", y  
        y ← y + h * f(t, y)  
        t ← t + h  
    FIN MIENTRAS  
FIN ALGORITMO  

🌀 2. MÉTODO DE RUNGE-KUTTA 4TO ORDEN  
ALGORITMO MetodoRungeKutta4  
    ENTRADA: función f(t, y), intervalo [t0, tf], valor inicial y0, paso h  

    t ← t0  
    y ← y0  

    MIENTRAS t ≤ tf HACER  
        IMPRIMIR "t =", t, "y =", y  

        k1 ← h * f(t, y)  
        k2 ← h * f(t + h/2, y + k1/2)  
        k3 ← h * f(t + h/2, y + k2/2)  
        k4 ← h * f(t + h, y + k3)  

        y ← y + (k1 + 2*k2 + 2*k3 + k4) / 6  
        t ← t + h  
    FIN MIENTRAS  
FIN ALGORITMO  

🌀 3. MÉTODO DE TAYLOR  
ALGORITMO MetodoTaylor  
    ENTRADA: función f y sus derivadas f', f'', ..., f^(n), valor inicial t0, y0, paso h, orden n  

    t ← t0  
    y ← y0  

    MIENTRAS t ≤ tf HACER  
        IMPRIMIR "t =", t, "y =", y  

        y ← y + h * f(t, y) + (h^2 / 2!) * f'(t, y) + (h^3 / 3!) * f''(t, y) + ... + (h^n / n!) * f^(n-1)(t, y)  
        t ← t + h  
    FIN MIENTRAS  
FIN ALGORITMO  
