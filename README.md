<p align="center"><img src="docs/banner.svg" alt="KORE" width="100%"></p>

<p align="center"><i>Autoevaluación académica con mentores que evolucionan con vos.</i></p>

---

## Qué es

Una sola página (`HTML + Tailwind + JS`, sin build ni dependencias) para estudiar con sesiones tipo parcial, un mentor animado y progreso persistente en el navegador.

## Secciones

| | |
|---|---|
| ⌂ **Inicio** | Elegí modo secuencial o personalizado por fases |
| ❖ **Niveles** | Rango, XP y evolución de cada mentor |
| ◔ **Progreso** | Meta diaria, actividad y dominio por fase |
| ☷ **Historial** | Notas y sesiones anteriores |
| ✧ **Logros** | 18 hitos con barra de avance |
| 👔 **Armario** | 120 prendas, 12 diseños por categoría |

## Evolución por XP

```mermaid
flowchart LR
    A["0 XP<br/>Etapa 1"] --> B["150 XP<br/>Etapa 2"] --> C["500 XP<br/>Etapa 3"] --> D["1500 XP<br/>Etapa 4"] --> E["4000 XP<br/>Etapa 5"]
```

| Mentor | Primera forma | Forma final |
|---|---|---|
| Dr. Alfred 🐧 | Polluelo Zen | Ascendido de la Aurora |
| Dr. Panino 🐕 | Cachorro de Cátedra | Cerbero Supremo |
| Dr. Chiquistriquis 🐈 | Gatito Travieso | Bakeneko Cósmico |
| Dr. Moyin 🦫 | Capi Cachorro | Capibara Celestial |

## Flujo

```mermaid
flowchart LR
    S[Elegir modo] --> Q[Sesión de preguntas] --> X[XP + racha] --> E[Evolución] --> P[Progreso y logros]
```

## Uso local

Abrí `kore_the_intellectual_sanctuary_ics.html` en el navegador. Los datos se guardan en `localStorage`.

## Deploy

Sitio estático. En Vercel: *Framework Preset* **Other**, sin build command. `vercel.json` sirve el HTML en `/`.

---

<p align="center"><sub>KORE · hecho con calma</sub></p>
