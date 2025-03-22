# 🚢📊 Conclusiones del Caso Compass Maritime  

## 📌 Modelo Seleccionado: **Lasso Regression**  
✔️ **El mejor modelo identificado fue Lasso**, el cual se aplicó con regularización para optimizar la selección de predictores.  
✔️ Tanto **Lasso como OLS** presentan un error menor comparado con Ridge, indicando que la regularización Lasso es más efectiva para este caso.  

## 🔍 **Predictores Seleccionados**  
El modelo Lasso seleccionó **cinco variables clave** para la predicción del precio de venta de barcos:  

| 🏷️ Predictor | 📉 Coeficiente | 📌 Interpretación |
|-------------|-------------|----------------|
| **Age_at_Sale** | -3.420895 | A mayor edad del barco, menor es su precio de venta. |
| **Dead_Weight_Tons** | 0.259412 | Barcos con mayor peso tienden a valer más. |
| **Trailing_1_Year_Avg_Monthly_Baltic_Dry** | 0.005534 | Indicador del mercado marítimo que influye en los precios. |
| **Flag_fecha** | 34.838573 | La bandera bajo la cual opera el barco es un factor clave. |
| **Age_Sale_Flag** | -1.670431 | Relación negativa con el precio, similar a la edad del barco. |

## 📈 **Resultados de la Valuación**  
El modelo se aplicó para estimar los valores de venta, y los principales hallazgos fueron:  
🔹 Se logró una predicción con **menor error** en comparación con otros métodos.  
🔹 Se identificaron **factores críticos** que afectan el precio de venta de los barcos.  
🔹 Se recomienda utilizar este modelo como base para futuras valoraciones.  
