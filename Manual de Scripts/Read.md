# ScadaBR — Exemplos de Scripts JavaScript

Repositório de apoio ao **Manual de Scripts JavaScript para ScadaBR**, elaborado para a disciplina de Sistemas Supervisórios.

**Prof.ª Dra. Maria Aline Gonçalves**

---

## Como importar um exemplo no ScadaBR

1. Faça o download do arquivo `.json` do exemplo desejado.
2. No ScadaBR, acesse o menu **Importação/Exportação** (ícone de seta no menu superior).
3. Cole o conteúdo do arquivo JSON no campo de importação.
4. Clique em **Importar**.
5. O Data Source, os Data Points e o Script serão criados automaticamente.

---

## Estrutura dos exemplos

| Pasta | Seção do Manual | Descrição |
|---|---|---|
| `cap02-leitura-ponto/` | Seção 2.2 | Data Source Virtual + Script que lê valor e timestamp de um ponto |
| *(em breve)* | Seção 4 | Escrita em pontos com writeDataPoint |
| *(em breve)* | Seção 5 | Temporização com while() + Date().getTime() |

---

## Exemplos disponíveis

### `cap02-leitura-ponto/projeto_temperatura_sala.json`

Cria:
- **Data Source Virtual** (`DS_245196`) — atualização a cada 5 segundos
- **Data Point** `temperatura_sala` (`DP_593011`) — numérico, tipo Incremental, min 15°C, max 25°C
- **Script** `Temperatura` (`SC_183467`) — lê `p2.value` e `p2.time` do ponto

---

## Licença

Material didático de uso livre para fins educacionais.
