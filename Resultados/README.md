# Carpeta Resultados

Aquí está todo lo final del proyecto.

## Qué hay aquí

### 1. Predicciones finales (notebook)
El notebook con el modelo final entrenado y las 5 predicciones.

**Para ejecutar**:
1. Abrir en Jupyter/VS Code
2. Restart Kernel  
3. Run All
4. Tarda menos de 2 minutos

### 2. Informe Final (markdown)
El informe completo con todo lo que hicimos, más corto y directo.

**Para convertir a PDF**:
- Más fácil: Pandoc → `pandoc "Informe Final.md" -o informe.pdf`
- Online: markdown-pdf.com
- VS Code: Clic derecho → Export to PDF
- Manual: Copiar a Word/Google Docs → Guardar como PDF

## Resultados Rápidos

**Modelo ganador**: Regresión Lineal
- Error: 1 punto en promedio
- Precisión: 97%
- Tiempo: Menos de 1 minuto

**Predicciones**: Error de 0.5 en 5 juegos muy diferentes

## Lo Necesario

- Python 3.8+
- pandas, numpy, scikit-learn
- El entorno: `proyectoIAEnv`

## Más Info

Revisa los notebooks en:
- `EDA/` - Exploración de datos
- `Data_Prep/` - Limpieza
- `Experiment/` - Todos los modelos que probamos

