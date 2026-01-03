# Analisis_Estacionalidad

Carga de datos: Importamos el archivo ClimaCDMX2021.csv usando la librería pandas. Este archivo contiene dos columnas principales: el mes (del 1 al 12) y la temperatura máxima registrada.

Selección de variables: Con el comando iloc, separas los datos: la variable mes se asigna al eje horizontal (X) y climaxmax (la temperatura) al eje vertical (Y).

Gráfica de tendencia: El código genera una línea roja que muestra el comportamiento del clima. En la imagen se ve claramente un pico entre los meses 3 y 5 (marzo a mayo), que es la temporada más calurosa en CDMX, y una caída hacia el final del año (invierno).

Propósito del análisis: Aunque usas herramientas similares a las de ARIMA, aquí no estás prediciendo el futuro todavía; estás haciendo una exploración visual para confirmar que los datos tienen un ciclo que se repite cada año.
<img width="1251" height="781" alt="image" src="https://github.com/user-attachments/assets/dc22fb68-936b-4bdd-a029-d14d7d207bb0" />
