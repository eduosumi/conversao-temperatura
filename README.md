premissas:
 - ter uma imagem docker disponivel na maquina em questao ou no Registry de imagem docker como por exemplo Docker Hub(é necessario fazer login no terminal para ser possivel fazer o pull da imagem);
 - startar um cluster k8s;
 
 executar:
 - acessar o diretorio que consta o arquivo .yaml com as instrucoes do k8s
 - kubectl apply -f deplyment.yaml
 - acessar pelo browser: localhost:30000