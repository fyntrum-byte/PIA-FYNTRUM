# Fyntrum — Portfolio & Investment Advisor

Herramienta interna de asesoría de portafolio de inversiones para clientes individuales.

## Servicio
**Asesoría Anual de Portafolio — $999/año**

Construcción y seguimiento de portafolio diversificado:
- 40% Riesgo Bajo (ETFs, Dividend Stocks, Bonos)
- 30% Riesgo Medio (Growth Stocks, Commodities, REITs)
- 30% Riesgo Alto (Crypto, CFDs, Especulativos)

## Módulos

| Módulo | Descripción |
|---|---|
| Política de Inversión | Perfil del cliente, restricciones, reglas de salida |
| Constructor de Portafolio | Distribución 40/30/30 con donut chart dinámico |
| Análisis de Activos | Acciones (Graham/DCF), ETFs, Crypto, Commodities |
| Radar de Oportunidades IA | Señal comprar/mantener/esperar con tesis y niveles |
| Seguimiento | P&L en tiempo real, alertas de stop loss |
| Informe Mensual IA | Reporte para el cliente generado automáticamente |

## Uso
Abre `index.html` en el navegador o accede al dominio de Vercel.

Ingresa tu **Anthropic API Key** en el sidebar para activar el Asistente IA, el Radar de Oportunidades y el Informe Mensual.

## Stack
- HTML / CSS / JavaScript puro — sin dependencias de build
- Chart.js (CDN) para el donut chart de distribución
- Anthropic API (Haiku 4.5) para análisis IA
- Tabler Icons (CDN) para iconografía

## Costo de API estimado
~$0.17 por cliente al año con uso normal (24 análisis + 12 informes + 60 mensajes de chat).

## Deploy en Vercel
1. Sube este repositorio a GitHub
2. Importa el repo en [vercel.com](https://vercel.com)
3. Deploy automático — sin configuración adicional

---
*Fyntrum · Inteligencia en Inversiones · v1.0 — Uso interno exclusivo*
