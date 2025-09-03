# cp4-ia

## 👥 Integrantes
### Caio Henrique - RM 554600
### Carlos Eduardo - RM 555223
### Antônio Lino - RM 554518

## 📊 Datasets Utilizados

### 1. Individual Household Electric Power Consumption
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)  
- **Descrição:** Medições de consumo elétrico em uma residência ao longo de quase 4 anos (2006–2010).  
- **Formato:** `household_power_consumption.txt` (aprox. 20 MB, separado por `;`)  
- **Número de observações:** 2.075.259 linhas  
- **Número de variáveis:** 9  

#### Variáveis principais:
- `Date` → Data (dd/mm/yyyy)  
- `Time` → Hora (hh:mm:ss)  
- `Global_active_power` → Potência ativa global (kW)  
- `Global_reactive_power` → Potência reativa global (kVar)  
- `Voltage` → Voltagem (V)  
- `Global_intensity` → Corrente global (A)  
- `Sub_metering_1` → Consumo da cozinha (Wh)  
- `Sub_metering_2` → Consumo da lavanderia (Wh)  
- `Sub_metering_3` → Consumo do aquecedor/ar-condicionado (Wh)  

---

### 2. Appliances Energy Prediction
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)  
- **Descrição:** Dados de consumo de energia de eletrodomésticos junto com variáveis ambientais internas e externas (2016).  
- **Formato:** `energydata_complete.csv`  
- **Número de observações:** 19.735 linhas (cada linha = 10 minutos de leitura)  
- **Número de variáveis:** 29  

#### Variáveis principais:
- `Appliances` → Consumo de energia (Wh) dos eletrodomésticos  
- `lights` → Consumo de energia das luzes (Wh)  
- `T1...T9` → Temperaturas em diferentes áreas da casa (°C)  
- `RH_1...RH_9` → Umidades relativas em diferentes áreas da casa (%)  
- `T_out` e `RH_out` → Temperatura e umidade externas  
- `Windspeed` → Velocidade do vento (m/s)  
- `Visibility` → Visibilidade (km)  
- `Tdewpoint` → Temperatura do ponto de orvalho (°C)  

---

## ⚙️ Instruções de Execução

### 1. Clonar o repositório
```bash
git clone <link-do-seu-repo>
cd checkpoint01
