# PvZ2 Gardendless: Traducción al español latino

Mod de traducción al **español latino** para **PvZ2 Gardendless**, hecho para **GP-Next**. Corrige la traducción al español que trae el juego y usa los nombres de plantas, zombis y mundos de la [Wiki de Plants vs. Zombies en español](https://plantsvszombies.fandom.com/es).

## Instalación

1. **Descarga el mod en .zip.** Tienes dos opciones:
   - En [**Releases**](../../releases/latest), descarga `TraduccionLatinaGardenless.zip`.
   - O en esta página, usa el botón verde **Code → Download ZIP**.

   **No descomprimas el archivo**: se importa tal cual.
2. Abre el juego y presiona **F9** (o el botón de arriba a la izquierda) para abrir el panel de **GP-Next**.
3. En la pestaña **Mods**, elige **Importar ZIP** y selecciona el archivo que descargaste.
4. **Activa** el mod, **guarda** la selección y **aplica**. Si el juego te pide reiniciar, hazlo.
5. En los **ajustes del juego**, elige **Español** como idioma.

Para comprobar que funciona, busca a la **Apisonaflor** en el almanaque o mira la **Playa de la Gran Ola** en el mapa de mundos.

## Requisitos

- La versión más reciente de **PvZ2 Gardendless**.
- **GP-Next 1.5.4** o más reciente.

Si al iniciar aparece el error `Native build identity is unavailable`, actualiza el juego a la versión más reciente desde [pvzge.com](https://pvzge.com). Con eso se resolvió en las pruebas.

## Qué cambia

- **Nombres de plantas y zombis** según la wiki en español: Apisonaflor, Papapum, Coltapulta, Hielaguisantes, Planta carroñívora, Zombictor, Yeti del tesoro, y la terminología de variantes (*caracono*, *caracubo*, *abanderado*, *Zombidito*, *Zombistein*).
- **Mundos**: Playa de la Gran Ola, Vueltacasete de Neón, Cuevas Congeladas, Pantano del Jurásico, Tiempos Modernos y Templo Kung Fu.
- **Consejos de la pantalla de carga**: estaban desfasados (cada consejo mostraba el texto de otro). Ahora coinciden y se tradujeron los que faltaban.
- **Textos que no tenían español**: interfaz (piñatas, minijuegos, premios, eventos) y el almanaque de las plantas y zombis más nuevos.
- **Almanaque**: los textos que mencionaban plantas o zombis por su nombre en inglés ahora usan el nombre en español.
- **Ortografía y regionalismos**: tildes y eñes que faltaban, y expresiones de España adaptadas al español latino.

## Contenido del mod

| Archivo | Qué traduce |
|---|---|
| `pack.json` | Datos del mod para GP-Next |
| `jsons/lang/lang.json` | Interfaz, mundos y consejos de carga |
| `jsons/features/PlantFeatures.json` | Nombres de plantas |
| `jsons/features/ZombieFeatures.json` | Nombres de zombis |
| `jsons/objects/PlantAlmanac.json` | Almanaque de plantas |
| `jsons/objects/ZombieAlmanac.json` | Almanaque de zombis |

## Errores o sugerencias

Si encuentras un texto mal traducido, abre un [Issue](../../issues) con el texto que ves en el juego y cómo debería decir.

## Aviso

Proyecto de fans, sin relación con Electronic Arts, PopCap Games ni el equipo de PvZ2 Gardendless. *Plants vs. Zombies* es una marca de Electronic Arts. Los nombres en español se basan en la Wiki de Plants vs. Zombies en español.
