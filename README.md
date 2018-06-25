# Teste de Front-end NeosaCode
Este teste é apresentado aos candidatos as vagas de desenvolvimento Front-end para avaliar os quesitos técnicos.

### O Desafio

Seu objetivo é criar um simples app que deve conter duas páginas, uma que exibe um formulário com os campos abaixo, e outra que liste os dados cadastrados.

* Nome completo
* CPF
* Telefone
* Email

### Pré-requisitos: 
 - Deve ser possível criar, listar e excluir os dados cadastrados pelo formulário;
 - Os inputs de texto e botão devem ter a aparência conforme o guia de estilo abaixo (com validações);
 - Fazer a persistência dos dados no `localStorage` ou `IndexedDB`;
 - Não é permitido a utilização de nenhum framework ou o uso de qualquer biblioteca (exceto para testes unitário e tasks de build), recomandado uso de ECMAScript 6+;

Para ter o estado inicial da lista de usuário utilizar este recurso abaixo:

Response:

```json

[
  {
    "name": "My name 1",
    "cpf": "04080757247",
    "phone": "11987654321",
    "email": "myemail1@test.com.br"
  },
  {
    "name": "My name 2",
    "cpf": "77797584192",
    "phone": "11987654321",
    "email": "myemail2@test.com.br"
  },
  {
    "name": "My name 3",
    "cpf": "45486737688",
    "phone": "11987654321",
    "email": "myemail3@test.com.br"
  }
]
```

A partir deste ponto utilizar o `localStorage/IndexedDB` para persistir localmente as informações.

Save:

```json
{
  "name": "My name 4",
  "cpf": "74668869066",
  "phone": "11987654321",
  "email": "myemail4@test.com.br"
}
```

Lista local:
```json
[
  {
    "name": "My name 1",
    "cpf": "04080757247",
    "phone": "11987654321",
    "email": "myemail1@test.com.br"
  },
  {
    "name": "My name 2",
    "cpf": "77797584192",
    "phone": "11987654321",
    "email": "myemail2@test.com.br"
  },
  {
    "name": "My name 3",
    "cpf": "45486737688",
    "phone": "11987654321",
    "email": "myemail3@test.com.br"
  },
  {
    "name": "My name 4",
    "cpf": "74668869066",
    "phone": "11987654321",
    "email": "myemail4@test.com.br"
  }
]
```

### Plus:
 - A página ser responsiva;
 - Permitir edição;
 - Uso de pré-processador css;
 - Testes End to End;

### O que esperamos:
 - Utilizar ECMAScript 6+;
 - Criar uma breve descrição da solução utilizada.


## Guia de estilo

### Input:
 - Cor da fonte sem foco: <span style="color:#efeeed">*#efeeed*</span>.
 - Cor da fonte com foco: <span style="color:#333333">*#333333*</span>.
 - Cor da borda: <span style="color:#efeeed">*#efeeed*</span>.

![inputs](./images/name.png)

### Input Inválido:
 - Cor da fonte: <span style="color:#eb4a46">*#eb4a46*</span>.
 - Cor da borda: <span style="color:#eb4a46">*#eb4a46*</span>.

![inputs](./images/name_validation.png)

### Botão Abilitado:
 - Cor da fonte com foco: <span style="color:#ffffff">*#ffffff*</span>.
 - Cor de background: <span style="color:#00c8b3">*#00c8b3*</span>.

![inputs](./images/button_enable.png)

### Botão Hover:
 - Opacidade do botão com hover: 70%.

![inputs](./images/button_enable_hover.png)

### Botão Desabilitado:
 - Cor da fonte sem foco: <span style="color:#dddcdc">*#dddcdc*</span>.
 - Cor de background: <span style="color:#f6f6f6">*#f6f6f6*</span>.

![inputs](./images/button_disable.png)

### Botão Loading:

![inputs](./images/button_enable_loading.png)

**Criar animação de loading ao clicar no submit*

### Exemplo final

![inputs](./images/form.png)

** Use sua criatividade para criar a página para listar os dados cadastrados **
