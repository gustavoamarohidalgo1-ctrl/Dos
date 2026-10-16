# Dos programas de agencias de empleo

Programas de escritorio (Python, Tkinter y SQLite) para registrar clientes y trabajadoras, asignarlas, preparar, firmar e imprimir contratos (Word o PDF), cobrar comisiones y llevar las garantías. Cada carpeta es un programa completo, con sus pruebas, sus instaladores y su propia guía (`README.md` y `LEEME.txt`).

| Carpeta | Programa | Versión | Viene de |
| --- | --- | --- | --- |
| [Servicio-Exclusivo](Servicio-Exclusivo) | Agencia de Empleos «Servicio Exclusivo» | Windows 1.8.0 · Mac 1.7.1 | [Tia_Programa](https://github.com/gustavoamarohidalgo1-ctrl/Tia_Programa), rama `prueba-1.8.0`, commit `b3c4e35` |
| [Servitotal](Servitotal) | Agencia de Empleos «S.T Servitotal» | Windows 1.9.0 · Mac 1.7.1 | [PrimaXiomara](https://github.com/gustavoamarohidalgo1-ctrl/PrimaXiomara), rama `prueba-1.9.0`, commit `a816a7c` |

- **Servitotal es el mismo programa que Servicio Exclusivo**, con sus colores, sus datos (nombre, contrato, carpeta de datos) y, desde la 1.9.0, los **avisos** y las **finanzas del día** en Ganancias. Su `agencia.py` se genera desde el de Servicio Exclusivo con [`Servitotal/instaladores/construccion/igualar_con_tia.py`](Servitotal/instaladores/construccion/igualar_con_tia.py).
- **Instaladores de Windows (64 bits):** [`Servicio-Exclusivo/instaladores/Agencia-de-Empleos-Windows-x64.exe`](Servicio-Exclusivo/instaladores) y [`Servitotal/instaladores/Servitotal-Windows-x64.exe`](Servitotal/instaladores). Sus huellas están en el `SHA256SUMS.txt` de cada carpeta. Ambos se probaron en Windows Server 2022 y 2025 con GitHub Actions en sus repositorios de origen; aquí los flujos de `.github` de cada carpeta no se ejecutan, porque GitHub solo ejecuta los de la raíz.
- **Sin datos de las agencias:** clientes, trabajadoras, contratos y copias de seguridad se guardan aparte, en la carpeta de datos de cada computadora, y no están en este repositorio.
- El historial completo de cambios sigue en los dos repositorios de origen.
