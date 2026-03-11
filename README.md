TelecomX - Análisis de Churn de Clientes

📋 Descripción del Proyecto
Este proyecto analiza la fuga de clientes (churn) de la empresa de telecomunicaciones TelecomX utilizando técnicas de análisis de datos en Python. El objetivo es identificar los factores que influyen en la decisión de los clientes de abandonar el servicio y proporcionar recomendaciones estratégicas para mejorar la retención.

🎯 Objetivos
- Analizar la tasa de abandono (churn) de clientes de TelecomX
- Identificar patrones y factores que influyen en la decisión de los clientes de cancelar el servicio
- Visualizar distribuciones de churn según diferentes variables (género, tipo de contrato, método de pago)
- Proporcionar recomendaciones basadas en datos para reducir la tasa de abandono

📊 DatasetFuente: 

TelecomX Data JSONCaracterísticas principales:
Datos de clientes con información demográfica
Información de servicios contratados (teléfono, internet)
Detalles de cuenta (tipo de contrato, método de pago, facturación)
Variable objetivo: Churn (1 = cliente se fue, 0 = cliente permanece)

📊 Hallazgos Clave

El análisis revela que el género no influye en el abandono (diferencia de solo 0.7%), mientras que los contratos mensuales presentan una tasa alarmante de 42.7% versus apenas 2.8% en contratos de dos años. Esto indica que los clientes con compromisos cortos evalúan constantemente si continuar, creando múltiples puntos de salida.

El método de pago es igualmente crítico. Los clientes que usan cheque electrónico abandonan al 45.3%, mientras que quienes tienen pago automático solo lo hacen en 15-17%. La fricción mensual de pagar manualmente se convierte en un momento de reflexión que favorece la cancelación, mientras que la automatización elimina estos puntos críticos de decisión.

El perfil de máximo riesgo combina contrato mensual con cheque electrónico, probablemente superando 60-70% de abandono. Este segmento representa la mayor oportunidad de mejora con intervenciones específicas.

