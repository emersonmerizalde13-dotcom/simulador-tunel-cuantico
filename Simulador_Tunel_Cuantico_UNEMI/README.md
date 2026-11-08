# Simulador del efecto túnel cuántico — UNEMI

## Abrir en Visual Studio Code
1. Extrae el ZIP y abre la carpeta `Simulador_Tunel_Cuantico_UNEMI` con **Archivo > Abrir carpeta**.
2. Instala la extensión **Live Server** (Ritwick Dey) en Extensiones.
3. Haz clic derecho en `index.html` y selecciona **Open with Live Server**.
4. Cambia energía, altura y ancho. Observa resultados y gráficas.
5. Para guardar ensayos, introduce **código** y **grupo**; luego utiliza **Guardar ensayo**.

## Modelo
Barrera rectangular unidimensional, electrón no relativista, estados estacionarios y sin absorción. Calcula transmisión T y reflexión R para E menor, igual o mayor que V0. No simula propagación temporal de paquetes de onda. Los SVG muestran potencial y curva teórica de transmisión. El prototipo no depende de bibliotecas externas.

## Verificación sugerida
- Valores iniciales: E=1 eV, V0=2 eV, a=0.5 nm.
- Comprobar T+R=1.
- Manteniendo E<V0 y V0 fijos, al aumentar a debe disminuir T.
- Probar E=V0 y E>V0.
- Comparar los cálculos con una fuente académica independiente antes de la entrega.

## Alcance
Este avance incluye HTML, CSS y JS, controles sincronizados, dos representaciones SVG, resultados, registro local, comparación y CSV. Pendiente para versión final: exportación XLSX auténtica, retos pedagógicos completos y visualización físicamente calculada de la función de onda.
