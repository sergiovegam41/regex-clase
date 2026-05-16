# Clase de Expresiones Regulares — Paso a Paso

Una página (estilo presentación / stepper) construida con **HTML, CSS y JavaScript puros**, sin frameworks ni dependencias.

**🌐 En vivo:** https://sergiovegam41.github.io/regex-clase/

## Objetivo

Exponer y enseñar expresiones regulares en 6 pasos, repartidos entre 2 expositores. Cada paso tiene:
- **Izquierda:** un formulario en vivo con validación y feedback de error.
- **Derecha:** la expresión regular aplicada con descripción explicativa.

## Distribución de los pasos

| # | Tema | Expositor | Dificultad |
|---|------|-----------|------------|
| 1 | Definición + operadores básicos | Expositor 1 | ●○○ |
| 2 | Validación de letras (nombres)   | Expositor 2 | ●○○ |
| 3 | Validación de números (teléfono) | Expositor 1 | ●●○ |
| 4 | Validación de correos             | Expositor 2 | ●●○ |
| 5 | Secuencias binarias sin "11" consecutivos | Expositor 1 | ●●● |
| 6 | Detectar correos dentro de un texto | Expositor 2 | ●●● |

Cada expositor tiene 1 tema fácil, 1 medio y 1 difícil.

## Cómo verlo

### Opción 1 — En línea
Abre https://sergiovegam41.github.io/regex-clase/ desde cualquier navegador.

### Opción 2 — Local (Termux)
No necesita servidor (es 100% estático):

```bash
cd ~/downloads/regex-clase
termux-open index.html
```

O abre el archivo desde el explorador de archivos del teléfono haciendo tap en `index.html`.

## Atajos de teclado

- `→` siguiente paso
- `←` paso anterior
- Click en cualquier "pill" del stepper para saltar directo

## Estructura

```
regex-clase/
├── index.html   # todo en un solo archivo (HTML + CSS + JS)
└── README.md
```
