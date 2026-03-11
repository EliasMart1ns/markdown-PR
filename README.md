# Style Guide do Projeto
## Linguagem Typescript
### Variáveis
```
Sempre adicione a tipagem primitiva.
```

```
//Ruim
nome = "VAI CORINTHIANSSS";
nome = any = "VAI CORINTHIANSSS";

//Bom
nome = string = 'Sem Mundial';
```
---

```
Evite o uso de ELSE.
```

```
//ruim
if (a == b)
    console.log('iguais')
else
    console.log('diferentes')

//bom
if (a == b)
    console.log('iguais')
if (a != b)
    console.log('diferentes')
```

