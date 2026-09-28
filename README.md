# Taller 1 — Supervisión de contratación pública de bienes (SECOP II)

**MINE-4101 Ciencia de Datos Aplicada · Universidad de los Andes · 2026-20**

## Integrantes
- Julieth Dayanna Rodríguez Animero — 202312585

## Objetivo
Identificar qué características de un contrato público de bienes (valor, modalidad, destino del gasto, sector) se asocian con desviaciones en su ejecución, para que la oficina de control interno focalice la supervisión desde el momento de la firma.

## Alcance
- Datos: 196.391 contratos de compraventa y suministro de SECOP II firmados entre 2019 y 2025.
- Periodo analítico: 2021–2024. Se excluyeron 2019–2020 por la alta proporción de contratos aprobados sin ejecutar y 2025 por el peso de contratos todavía en curso.
- Indicadores: (1) adición de plazo registrada, en todos los contratos firmados en 2021–2024; (2) proporción pagada del valor contractual, solo en contratos terminados o cerrados.
- Técnicas: estadística descriptiva, chi-cuadrado, Kruskal–Wallis, Mann–Whitney, Cochran–Armitage, Spearman, ajuste de Holm, tamaños de efecto y bootstrap por entidad.

## Principales hallazgos (insights)
1. **El valor del contrato es el mejor predictor de ampliaciones de plazo.** El 15,2 % de los contratos de más de 140 millones tiene adiciones, frente al 2,8 % de los de menos de 10 millones (5,5 veces más). La tendencia se mantiene dentro de cada modalidad.
2. **Licitación pública amplía plazos 4,2 veces más que mínima cuantía** (25,5 % frente a 6,1 %). Selección abreviada y subasta inversa lo hacen alrededor del doble.
3. **Régimen especial y contratación directa concentran contratos cerrados sin pagos registrados.** Régimen especial con ofertas llega al 80,8 %, y al 84,1 % en funcionamiento.
4. **El sector es el factor con más efecto sobre el pago cero:** salud 69,9 % y transporte 56,9 %.
5. **Hay 911 contratos de mínima cuantía por encima del tope legal de 100 SMMLV,** con 2,5 veces más adiciones. Es una alerta de calidad y de riesgo.
6. **No significativos:** contratación directa no difiere de mínima cuantía en adiciones (p ajustado = 0,70), y el valor del contrato no tiene relevancia práctica sobre el pago (ρ = −0,07).

## Organización del repositorio
