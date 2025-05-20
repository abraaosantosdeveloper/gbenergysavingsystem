
### “Caçando desperdícios invisíveis para salvar energia, dinheiro e o planeta.”

---

## 🎯 Objetivo

Detectar aparelhos eletroeletrônicos em **modo stand-by** que continuam consumindo energia, mesmo quando parecem desligados.  
Alertar o usuário para desligá-los da tomada, promovendo **economia de energia e redução de emissão de CO₂**.

---

## ❓Principais questões

Para nos ajudar a enxergar a importância desse sistema, responderemos às seguintes perguntas:

- Como isso beneficia o usuário?
  - Economia de energia e dinheiro: Redução de desperdício ao identificar aparelhos em stand-by com consumo desnecessário;
  - Conscientização energética: Visão em tempo real do desperdício invisível(Educação sustentável);
  - Facilidade de uso: Simples, portátil e intuitivo;
  - Segurança: Evita o superaquecimento causado por dispositivos ligados simultâneamente.
- Qual a eficiência?
   - Varia com a precisão do sensor de corrente(deve ser sensível o suficiente para identificar, por exemplo, consumos abaixo de `5w - aparelhos em standby`);
   - Resposta quase instantânea(menos de 1 segundo);
   - Com o uso de um relé inteligente, a alimentação é cortada automaticamente.
- Qual o percentual de redução de consumo?
  - de 10% a 15%, que é o consumo médio de aparelhos em stand-by como consoles, Tv, Micro-ondas, Carregadores e Pcs em repouso.
    > Fontes: IEA (International Energy Agency), Inmetro, Procel/Eletrobras.
- Por que, necessariamente reduz as emissões de CO2?
  - Cada kWh de energia elétrica gerado (no Brasil, ainda em parte por termoelétricas) libera uma quantidade de CO₂ equivalente:
    
    🔹 Em média:
    0,08 a 0,13 kg de CO₂ por kWh no Brasil (mais limpo), e até 0,7 kg de CO₂ por kWh em países com matriz fóssil (como EUA ou China).
    
    💡 Se uma casa economizar 30 kWh/mês com o projeto, isso evita:
    
    2,4 kg de CO₂/mês no Brasil
    
    21 kg de CO₂/mês em países com matriz fóssil
    
    → Multiplicado por milhares de casas, o impacto é massivo em escala urbana.
- Qual o impacto real?
  Na prática individual:

  ##### Redução direta da conta de luz.
  
  Estímulo à cultura de economia e sustentabilidade.
  
  Incentiva a desconexão de aparelhos que parecem “desligados”.
  
  ##### Na sociedade:
  
  Pode ser adotado por escolas, ONGs, prefeituras, áreas rurais.
  
  Pode ser produzido em oficinas maker ou kits de educação ambiental.
  
  Cria um canal de educação ambiental com eletrônica aplicada — sustentável e replicável.
  
  ##### No planeta:
  
  Em larga escala, reduz demanda por energia.
  
  Reduz CO₂ e poluição.
  
  Promove o uso de tecnologia verde acessível, especialmente com alimentação solar.

---

## 🧠 Conceito do Projeto

O **GBES²** utiliza um **Arduino** com sensor de corrente para:
- Medir consumo de energia em tempo real;
- Detectar consumo abaixo de um certo limiar (ex: 5W), típico de stand-by;
- Alertar o usuário com LEDs, som ou mensagem no display;
- Exibir economia estimada em **R$** e **CO₂ evitado**.

---
## Esquema do projeto

![Ghost Buster - Energy Saving System](https://github.com/user-attachments/assets/d9677084-83b8-4a6a-ad5e-8e775ac69378)



---

## 🛠️ Componentes Principais

- Arduino Uno ou Nano  
- Sensor de corrente ACS712 ou SCT-013  
- Display LCD 16x2 ou OLED  
- LED RGB (Verde = OK, Vermelho = Stand-by detectado)  
- Buzzer (opcional)  
- Relé (opcional para desligamento automático)  
- Fonte solar ou alimentação via USB  

---

## 🌱 Sustentabilidade e Eficiência

| Item                              | Descrição                                                                 |
|-----------------------------------|---------------------------------------------------------------------------|
| **Consumo Fantasma**              | Até 15% da energia residencial pode ser desperdiçada com aparelhos em stand-by |
| **Eficiência do Sistema**         | Detecta correntes mínimas com precisão (~mA), resposta rápida (<1s)        |
| **Redução de Energia Elétrica**   | Estimativa de 10% a 15% na conta de luz com uso consciente                |
| **Redução de CO₂**                | Evita até 21 kg de CO₂/mês em regiões com matriz fóssil (EUA/China)      |
| **Energia Limpa**                 | Projeto pode ser alimentado com painel solar                              |

---
## Consumo médio(semanal | Mensal)

![image](https://github.com/user-attachments/assets/079af0ff-680b-4b7f-baa3-6fcaa8030876)

---

## 💡 Benefícios para o Usuário

- Economia na conta de luz  
- Maior consciência ambiental e energética  
- Sistema portátil, educativo e aplicável em qualquer tomada  
- Pode ser utilizado em escolas, oficinas, comunidades e residências  
- Reduz riscos de aquecimento e curtos por consumo constante  

---

## 🌍 Impacto Esperado

- **Individual**: Economia e mudança de hábito  
- **Social**: Ferramenta educativa para escolas e ONGs  
- **Ambiental**: Menor emissão de CO₂ e menor demanda elétrica  
- **Tecnológico**: Demonstração real de como a eletrônica pode ser uma aliada do meio ambiente  

---

## 🔁 Possíveis Expansões Futuras

- App para visualizar o consumo e economia em tempo real  
- Integração com Wi-Fi e banco de dados (IoT)  
- Interface web para análise de consumo por cômodo ou aparelho  
- Otimização para uso em ambientes comerciais  

---

## 📌 Conclusão

O **GBES²** é uma proposta **simples, viável e escalável** de aplicar a Eletrônica Sustentável em um problema real: o **consumo invisível de energia elétrica**.  
Com baixo custo e alta aplicabilidade, o sistema **combate o desperdício**, promove **consciência ambiental** e **reduz as emissões de carbono** com tecnologia acessível.

---

## 👨‍🔧 Autor:  
*Abraão Filipi dos Santos – Tópicos de engenharia 1*  
