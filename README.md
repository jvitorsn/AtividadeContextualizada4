# AtividadeContextualizada4

Essa atividade visa emular um sistema de caixa de Skinner com o funcionamento abaixo, sem utilizar estruturas de repetição:

Requisito
		1: Habituação
	    Se			o animal está habituado, registrar em uma variável
      
Requisito
		2: Regime de aproximações sucessivas
    
    Iniciar			a variável com 30cm
    Se			a variável de aproximação diminuiu (animal aproximou), liberar 0,5ml de rec
    Se      animal tocou na barra 20x, retornar que o experimento passou para	a próxima etapa
    Se      o som1 foi emitido e o animal tocou na barra esquerda, liberar 0,5ml de rec
      Senão não liberar nada			
    Se    	o som2 foi emitido e o animal tocou na barra direita, liberar 0,5ml de rec
      Senão não liberar nada	
    Se o experimento foi realizado 50x em 30min, apresentar que o experimento seguirá para a próxima fase.
