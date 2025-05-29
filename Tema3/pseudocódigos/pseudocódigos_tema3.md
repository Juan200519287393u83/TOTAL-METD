# PSEUDOCÓDIGOS DE MÉTODOS NUMÉRICOS PARA SISTEMAS DE ECUACIONES LINEALES

🌀 1. ELIMINACIÓN GAUSSIANA  
ALGORITMO EliminacionGaussiana  
    ENTRADA matriz A[n][n], vector b[n]  

    PARA k ← 1 HASTA n-1 HACER  
        PARA i ← k+1 HASTA n HACER  
            factor ← A[i][k] / A[k][k]  
            PARA j ← k HASTA n HACER  
                A[i][j] ← A[i][j] - factor * A[k][j]  
            FIN PARA  
            b[i] ← b[i] - factor * b[k]  
        FIN PARA  
    FIN PARA  

    // Sustitución hacia atrás  
    x[n] ← b[n] / A[n][n]  
    PARA i ← n-1 HASTA 1 PASO -1 HACER  
        suma ← 0  
        PARA j ← i+1 HASTA n HACER  
            suma ← suma + A[i][j] * x[j]  
        FIN PARA  
        x[i] ← (b[i] - suma) / A[i][i]  
    FIN PARA  

    IMPRIMIR "Solución:", x  
FIN ALGORITMO  

🌀 2. ELIMINACIÓN DE GAUSS-JORDAN  
ALGORITMO EliminacionGaussJordan  
    ENTRADA matriz A[n][n], vector b[n]  

    PARA k ← 1 HASTA n HACER  
        // Pivoteo  
        pivote ← A[k][k]  
        PARA j ← k HASTA n HACER  
            A[k][j] ← A[k][j] / pivote  
        FIN PARA  
        b[k] ← b[k] / pivote  

        PARA i ← 1 HASTA n HACER  
            SI i ≠ k ENTONCES  
                factor ← A[i][k]  
                PARA j ← k HASTA n HACER  
                    A[i][j] ← A[i][j] - factor * A[k][j]  
                FIN PARA  
                b[i] ← b[i] - factor * b[k]  
            FIN SI  
        FIN PARA  
    FIN PARA  

    x ← b  
    IMPRIMIR "Solución:", x  
FIN ALGORITMO  

🌀 3. MÉTODO DE GAUSS-SEIDEL  
ALGORITMO MetodoGaussSeidel  
    ENTRADA matriz A[n][n], vector b[n], vector x[n] (inicial), tolerancia, max_iteraciones  

    PARA iter ← 1 HASTA max_iteraciones HACER  
        PARA i ← 1 HASTA n HACER  
            suma1 ← 0  
            PARA j ← 1 HASTA i-1 HACER  
                suma1 ← suma1 + A[i][j] * x[j]  
            FIN PARA  

            suma2 ← 0  
            PARA j ← i+1 HASTA n HACER  
                suma2 ← suma2 + A[i][j] * x[j]  
            FIN PARA  

            x_nuevo ← (b[i] - suma1 - suma2) / A[i][i]  
            x[i] ← x_nuevo  
        FIN PARA  

        // Comprobar convergencia  
        SI diferencia entre x nuevo y viejo < tolerancia ENTONCES  
            IMPRIMIR "Solución:", x  
            SALIR  
        FIN SI  
    FIN PARA  

    IMPRIMIR "No convergió"  
FIN ALGORITMO  

🌀 4. MÉTODO DE JACOBI  
ALGORITMO MetodoJacobi  
    ENTRADA matriz A[n][n], vector b[n], vector x[n] (inicial), tolerancia, max_iteraciones  

    PARA iter ← 1 HASTA max_iteraciones HACER  
        x_nuevo ← vector vacío de tamaño n  

        PARA i ← 1 HASTA n HACER  
            suma ← 0  
            PARA j ← 1 HASTA n HACER  
                SI j ≠ i ENTONCES  
                    suma ← suma + A[i][j] * x[j]  
                FIN SI  
            FIN PARA  

            x_nuevo[i] ← (b[i] - suma) / A[i][i]  
        FIN PARA  

        // Comprobar convergencia  
        SI diferencia entre x nuevo y viejo < tolerancia ENTONCES  
            IMPRIMIR "Solución:", x_nuevo  
            SALIR  
        FIN SI  

        x ← x_nuevo  
    FIN PARA  

    IMPRIMIR "No convergió"  
FIN ALGORITMO  
