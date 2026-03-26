# Visión por Computadora - Tomate Cherry/Uva

## Desafíos Específicos

### vs. Tomate Saladette
- **Mayor densidad de objetos** (12-30+ frutos por racimo vs 4-8)
- **Oclusión más frecuente** entre frutos
- **Variación de tamaño** menos pronunciada
- **Estados de madurez mezclados** en el mismo racimo

## Tareas de Detección

### Prioridades
1. **Conteo de frutos** por racimo
2. **Clasificación de madurez** (verde, breaker, turning, rojo)
3. **Detección de defectos** (rajaduras, pudriciones)
4. **Segmentación de racimos**
5. **Estimación de rendimiento**

## Datasets

- [ ] Chaparral, Nayarit (caso de estudio inicial)
- [ ] Operaciones low-tech vs high-tech
- [ ] Diferentes variedades
- [ ] Diferentes condiciones de iluminación

## Modelos

- YOLOv8/v9 para detección
- Modelos de segmentación (Mask R-CNN, SAM)
- Clasificadores de madurez
- Estimadores de tamaño/peso

## Parámetros de Detección

### Métricas objetivo
- **Precisión de conteo:** >95%
- **Clasificación de madurez:** >90%
- **Velocidad:** >30 FPS (tiempo real)

---
_En construcción - Tomato AI 🍅_
