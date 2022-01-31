# Relógio Generous Burguer

![clock](https://github.com/GeovanniSantos/relogio-generous-burguer/blob/master/Animação.gif)

## Sobre o projeto

Uma simples aplicação em JavaScript utilizando DOM e funções.

```bash
# função

function atualizaRelogio() {	
			var data = new Date();
			var hora = data.getHours();
			var minuto = data.getMinutes();
			var segundo = data.getSeconds();

			if(hora < 10)
				hora = "0" + hora;

			if(minuto < 10)
				minuto = "0" + minuto;

			if(segundo < 10)
				segundo = "0" + segundo;

			var tempo = hora + ":" + minuto + ":" + segundo;
			document.getElementById("relogio").innerHTML = tempo;
		}
		setInterval(atualizaRelogio, 1000)
    
```

