## Expresses

## Recuperar o CPF

**Luís Gabriel, 223.456.789-00,20 de Março de 2003, (64) 99991-8525, P Bispo Dom Benedito, Mineiros**

**Expressão 1: \d{3}\.\d{3}\.\d{3}-\d{2}**

**Expressão 2: [0-9]{3}\.[0-9]{3}\.[0-9]{3}-[0-9]{2}**

**Resultado: 223.456.789-00**

## Recuperar CPF, sem mask

**Luís Gabriel, 22345678900,20 de Março de 2003, (64) 99991-8525, P Bispo Dom Benedito, Mineiros**

**Expressão 1: \d{3}\.?\d{3}\.?\d{3}-?\d{2}**

**Expressão 2: \d{3}\.{0,1}\d{3}\.{0,1}\d{3}-{0,1}\d{2}**

**Resultado: 22345678900**

### OBS:

**"\d..." Seleciona um digito de 0 a 9**

**[0-9] Seleciona um digito de 0 a 9**

**\d{3} Selecionar 3 dígitos seguidos**

**Utilizar o "?", afirma que o carácter anterior a esse sinal, não é obrigatório, ou seja é opcional**

**{0,1} Afirma q o caráter anterior é opcional --- Execute 0 vezes ou 1 vez**
