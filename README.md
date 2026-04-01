# 🚗 Desafio Lógica - Calculadora de Consumo de Combustível

## 📋 Descrição

Aplicação interativa desenvolvida em **JavaScript** que calcula o gasto diário com combustível com base na distância percorrida, consumo do veículo e pesquisa de preços em diferentes postos de gasolina.

## 🎯 Objetivo

Este projeto é um desafio de lógica de programação que demonstra conceitos fundamentais de JavaScript:
- Entrada de dados via `prompt()`
- Cálculos matemáticos
- Estruturas de repetição (loops)
- Manipulação de dados numéricos
- Saída em console e DOM

## ✨ Funcionalidades

✅ **Coleta de Informações:**
- Distância entre casa e trabalho (em km)
- Consumo médio do veículo (km/L)
- Pesquisa de preços em múltiplos postos

✅ **Cálculos Realizados:**
- Consumo necessário de combustível para a viagem
- Menor valor encontrado entre os postos pesquisados
- Média de preços pesquisados
- Gasto diário com combustível (ida e volta)

✅ **Exibição de Resultados:**
- Console (ferramentas do desenvolvedor)
- Página HTML (document.write)

## 🛠️ Tecnologias

- **HTML5** - Estrutura e renderização
- **JavaScript (ES6)** - Lógica e processamento

## 📦 Como Usar

### 1. Clonar o Repositório
```bash
git clone https://github.com/joaoribeiroodev/desafio_logica-js.git
cd desafio_logica-js
```

### 2. Executar o Projeto
Abra o arquivo `desafio_logica-js.html` diretamente no seu navegador:
- Duplo clique no arquivo
- Ou arraste para o navegador
- Ou use um servidor local (recomendado)

### 3. Entrada de Dados
O programa solicitará informações via prompts:
1. **Distância percorrida** (em km) - Ex: 15
2. **Consumo médio** (km/L) - Ex: 10
3. **Quantidade de postos** - Ex: 3
4. **Preços** - Digite o valor pesquisado em cada posto

### 4. Visualizar Resultados
Os resultados aparecem:
- **Na página**: Valores calculados formatados com 2 casas decimais
- **No Console**: Dados brutos para debug (F12 → Console)

## 📊 Exemplo de Execução

**Entrada:**
- Distância: 20 km
- Consumo: 10 km/L
- Postos: 2
- Preço Posto 1: R$ 5.50
- Preço Posto 2: R$ 5.30

**Saída Esperada:**
```
O consumo necessário em litros é 2.00 litros
O menor valor pesquisado é 5.30
A média dos valores pesquisados é 5.40
O gasto diário (ida e volta) é 21.20
```

## 📝 Estrutura do Código

```javascript
// 1. Coleta de distância e consumo
// 2. Cálculo do consumo necessário
// 3. Loop para pesquisa de preços
// 4. Determinação do menor valor
// 5. Cálculo da média de preços
// 6. Cálculo do gasto diário (2x consumo * menor preço)
```

## 🔧 Melhorias Futuras

- [ ] Adicionar validação de entrada
- [ ] Implementar interface gráfica (CSS + moderno)
- [ ] Armazenar histórico de cálculos
- [ ] Adicionar mais variáveis (pedágios, consumo por tipo de combustível)
- [ ] Gerar relatório em PDF

## 📄 Licença

Este projeto está aberto para fins educacionais.

## 👤 Autor

**João Ribeiro** - [@joaoribeiroodev](https://github.com/joaoribeiroodev)

---

⭐ Se este projeto foi útil, considere deixar uma estrela!
