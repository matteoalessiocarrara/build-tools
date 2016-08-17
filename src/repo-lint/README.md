Questo è un sistema per perfezionare automaticamente un repo. 

Nel makefile sono definite le regole (generazione del changelog, generazione del file AUTHORS ecc), che per essere eseguite necessitano di sapere dove si trova il repo. Quindi va definita sulla linea di comando di make la variabile REPO_ROOT.

Il makefile può essere installato nel sistema, e make andrà chiamato con l'opzione --file + definizione della variabile REPO_ROOT. Siccome è troppo faticoso, ho scritto un piccolo wrapper che fa questo in automatico.