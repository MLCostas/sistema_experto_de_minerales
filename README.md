# Sistema experto difuso para la identificación de minerales

Cuaderno de Google Colab / Jupyter que identifica minerales a partir de tres propiedades observables (color, brillo y dureza de Mohs) usando lógica difusa con `scikit-fuzzy`.

En lugar de responder con un único mineral, devuelve **todos los minerales compatibles con su grado de compatibilidad**, y avisa cuando ninguna regla se activa.

## Minerales incluidos
Talco, yeso, baritina, cuarzo, galena y pirita.

## Cómo usarlo
1. Abrí `SistemaExpertoDifuso_Minerales_CostasML.ipynb` en [Google Colab](https://colab.research.google.com) (Archivo → Abrir cuaderno → GitHub).
2. Ejecutá las celdas en orden.
3. Para probar tus propias mediciones, descomentá `iniciar_identificacion()` en la sección 4.

## Ejemplo
```
Color=1.5  Brillo=1  Dureza=3.25
  → Baritina: compatibilidad 100%
  → Yeso: compatibilidad 31%
```

## Qué incluye
- Funciones de pertenencia graficadas.
- Base de reglas explicada con una tabla de propiedades.
- Casos de prueba, incluido el caso límite que antes producía un error.
- Sección de limitaciones y próximos pasos.

## Autoría
María Luisa Costas — Lic. en Ciencias Biológicas (FaCENA-UNNE) y Tec. en Ciencia de Datos (UNDEC).
Trabajo práctico original de autoría propia; esta versión fue revisada y mejorada con asistencia de IA (Claude).
