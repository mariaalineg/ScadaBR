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

| Pasta | Capítulo do Manual | Descrição |
|---|---|---|
| `cap02-conceitos-fundamentais/` | Cap. 2 — Conceitos Fundamentais | Data Source Virtual + ponto temperatura_sala + script de leitura com `p2.value` e `p2.time` |
| `cap03-leitura-pontos/` *(em breve)* | Cap. 3 — Leitura de Pontos | Exemplos de pontos calculados e múltiplos sensores |
| `cap04-escrita-controle/` *(em breve)* | Cap. 4 — Escrita e Controle | Controle liga/desliga com `writeDataPoint` |
| `cap05-temporizacao/` *(em breve)* | Cap. 5 — Temporização | Set point com pausa usando `while` + `Date().getTime()` |

---

## Exemplos disponíveis

### `cap02-conceitos-fundamentais/projeto_temperatura_sala.json`

Cria:
- **Data Source Virtual** (`DS_245196`) — atualização a cada 5 segundos
- **Data Point** `temperatura_sala` (`DP_593011`) — numérico, tipo Incremental, min 15 °C, max 25 °C
- **Script** `Temperatura` (`SC_183467`) — demonstra adição de ponto ao contexto com variável `p2`, lendo `p2.value` e `p2.time`

---

## Licença

Material didático de uso livre para fins educacionais.
