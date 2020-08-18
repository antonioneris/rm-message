## Descrição

Com o objetivo de agilizar o delete de mensagens em lote em servidores Zimbra, criei este script que procura as mensagens de emails dentro da pasta inbox e as deleta caso o assunto do email seja correspondente ao mencionado.

Assim conseguimos deletar em todos os emails do servidor um email com o assunto " Assunto do email a ser deletado ".




## Comandos


Para deletar um email com o assunto " Teste assunto"

```
# rm-message -s dominio.com.br 'Teste assunto'
```

Para deletar todos emails enviados por uma email@dominio.com.br

```
# rm-message -f email@dominio.com.br 'Teste assunto'
```


