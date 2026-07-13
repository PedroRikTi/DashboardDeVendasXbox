

# 📊 Dashboard de Assinaturas | Xbox Game Pass

Este projeto tem como objetivo transformar uma base de dados de assinaturas do **Xbox Game Pass** em informações visuais e analíticas, utilizando conceitos de **data view**, **gráficos dinâmicos**, **filtros visuais** e **big numbers** para facilitar a tomada de decisão.

---

## 📂 Dados Utilizados

A base contém informações de assinantes, incluindo:
- **Subscriber ID**: Identificação única do assinante  
- **Name**: Nome do assinante  
- **Plan**: Tipo de plano (Core, Standard, Ultimate)  
- **Start Date**: Data de início da assinatura  
- **Auto Renewal**: Indica se há renovação automática  
- **Subscription Price**: Valor da assinatura  
- **Subscription Type**: Frequência (Mensal, Trimestral, Anual)  
- **EA Play Season Pass**: Participação no EA Play  
- **Minecraft Season Pass**: Participação no Minecraft Pass  
- **Coupon Value**: Valor de cupons aplicados  
- **Total Value**: Valor total consolidado  

Além disso, foram criados cálculos agregados:
- **Total Subs**: Quantidade de assinaturas ativas  
- **EA Play Total**: Soma dos valores de EA Play  
- **Minecraft Total**: Soma dos valores de Minecraft Pass  

---

## 🔄 Transformando Dados em Informações

O processo de análise seguiu estas etapas:
1. **Entendimento da base de dados** – leitura e organização dos campos.  
2. **Limpeza e estruturação** – padronização de valores e tratamento de nulos.  
3. **Criação de métricas** – soma de valores, contagem de assinaturas, segmentação por plano.  
4. **Visualização** – construção de gráficos dinâmicos e indicadores.  

---

## 📈 Importância do Data View

O **Data View** permite:
- Explorar dados de forma tabular antes da visualização.  
- Validar cálculos e métricas criadas.  
- Garantir consistência entre base e dashboard.  

---

## 🎨 Gráficos Dinâmicos e Filtros Visuais

Foram utilizados:
- **Gráficos de barras e colunas** para comparar planos e valores.  
- **Filtros interativos** para segmentar por tipo de assinatura, plano ou período.  
- **Slicers** para navegação rápida entre categorias.  

---

## 🖌️ Organização e Estilização do Dashboard

- Layout limpo e intuitivo.  
- Paleta de cores consistente com a identidade Xbox.  
- Destaque para métricas principais em **cards visuais**.  
- Uso de ícones e legendas para facilitar interpretação.  

---

## 🔢 Trabalhando com Big Numbers

Indicadores principais destacados:
- **Total de Assinaturas**  
- **Receita Total Consolidada**  
- **Participação EA Play e Minecraft Pass**  

Esses números fornecem uma visão rápida e estratégica do negócio.  

---

## 📌 Informações Contextuais

O dashboard não apenas mostra números, mas também:
- **Tendências de adesão** ao longo dos meses.  
- **Comparação entre planos** (Core, Standard, Ultimate).  
- **Impacto de cupons e passes adicionais** na receita.  

---

## 🚀 Instruções para Reprodução

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-repositorio/xbox-dashboard.git
