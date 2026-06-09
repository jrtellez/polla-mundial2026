# ⚽ Polla Mundial 2026 · Waka Waka

Predictor de marcadores para el Mundial 2026 (USA · Canadá · México). Un **modelo Poisson multivariable** que no elige el marcador más probable, sino el que **maximiza los puntos esperados** de la polla — sumando sus cuatro componentes:

- 🏆 Ganador / empate (1X2)
- ⚽ Goles de cada equipo (por separado)
- ➖ Diferencia de goles

Todo corre **100% en tu navegador** (un solo `index.html`, sin servidor, sin instalar nada). Tus cuotas y resultados se guardan localmente en el navegador.

## 🔧 Cómo usarlo

Abre la página (GitHub Pages) o haz doble clic en `index.html`. Puedes:

- **Editar las reglas de puntuación** y todo se recalcula al instante.
- **Activar/desactivar variables** del modelo para ver su efecto.
- **Mostrar entrada de cuotas**: pega las cuotas decimales (1/X/2) de tu casa de apuestas y el modelo las fusiona (las cuotas son el mejor predictor individual).
- **Mostrar resultados / validación**: ingresa los marcadores reales y obtén los puntos logrados + métricas de calibración (acierto de signo, Brier score, goles y empates reales vs esperados).

## 🔬 Variables del modelo (ancladas en evidencia)

Elo · valor de mercado del plantel (Transfermarkt) · jugadores en clubes top · edad/experiencia · confederación · localía de anfitrionas · **público/diáspora en sede neutral** · altitud · calor · husos horarios · cuotas (opcional).

Basado en la literatura de pronóstico de Mundiales: Groll & Schauberger (2018), Peeters (2018, *Int. J. Forecasting*) y el experimento natural de los *ghost games* del COVID sobre el efecto del público.

## ⚠️ Aviso

Modelo con fines recreativos. El fútbol tiene una componente de azar irreducible a nivel de partido; ningún modelo acierta siempre. Los ratings y valores son estimaciones editables.
