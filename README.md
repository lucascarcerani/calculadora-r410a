# Calculadora R-410A — Superaquecimento e Sub-resfriamento

Ferramenta web para técnicos de refrigeração e ar-condicionado. Você digita as pressões do manifold e as temperaturas dos tubos; ela calcula a **temperatura de evaporação e de condensação**, o **superaquecimento**, o **sub-resfriamento** e mostra o **diagnóstico mais provável** (falta de fluido, excesso, restrição, baixa vazão de ar).

**▶ Usar online:** https://lucascarcerani.github.io/calculadora-r410a/

## Recursos

- Pressão em **psig** ou **bar** manométrico
- Saturação do R-410A por interpolação logarítmica de tabela P-T (−30 a 60 °C)
- Indicadores com cor só para estado (normal / atenção / crítico)
- Funciona no celular, sem instalar nada e sem internet depois de carregada
- Tema claro e escuro automático

## Exemplo

| Leitura | Valor |
|---|---|
| Sucção | 118 psig → evaporação ≈ 4,3 °C |
| Tubo de sucção | 10,5 °C → superaquecimento ≈ 6 K |
| Líquido | 340 psig → condensação ≈ 40,5 °C |
| Linha de líquido | 35 °C → sub-resfriamento ≈ 5,5 K |

## Aviso

As faixas de referência (SH 5–8 K, SC 4–7 K) são genéricas. O valor correto depende do equipamento, do tipo de expansão e das condições de ar. Sempre consulte o fabricante.

## Próximos passos

- [ ] Outros fluidos (R-32, R-22, R-134a)
- [ ] Cálculo de carga térmica em BTU/h e TR
- [ ] Leitura automática de sensores via ESP32 + MQTT

## Autor

**Lucas Carcerani** — Carcerani Energia e Automação
