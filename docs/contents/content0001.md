

- Contrl + shft + p , digitar snippet
- Vá em preferences, selecione configure use snippets > new snippets ou crie para uma extensão

Exemplo do corpo

~~~ javascript
	"Print to console": { //nome do snippet
			"prefix": "log", //chamada do snippet
			"body": [  //codigo a ser injetado
				"console.log('$1');", //codigo que sera injetodo 
				"$2"
			],
			"description": "Log output to console" // descrição
		}

~~~

Apos adicionado, ja esta pronto para uso.