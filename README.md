# PLAYGROUND
## CONTAINERS X VIRTUAL MACHINES
São tecnologias de virtualizações que ajudam na execução de aplicativos isolados do hardware.
### CONTAINERS:
**Containers é o hardware na parte inferior que no topo desse hardware está o "Kernel", ele ajuda o software e o hardware a se comunicarem. No topo do Kernel está o "SO" chamado de sistema operacional, que pode ser chamado de "SO Host" porque ele hospedará todos os containers e no topo do "SO" está cada container em execução.**

### VIRTUAL MACHINES
**As Máquinas Virtuais trabalham no nível do hardware, são chamadas de "virtualização de hardware", e o que tem no hardware é o que chama-se de "hipervisor", responsável por criar instâncias virtualizadas de cada um dos componentes que compõe nossas máquinas, entre processadores, memória RAM, rede, placas; Tudo isso estão sendo virtualizadas pelo hipervisor.**

### ISOLAMENTO
**Com as máquinas virtuais o isolamento é das máquinas. Um exemplo seria imaginar uma camada de base, temos um servidor que está alocado em algum lugar, mas queremos pegar nossos recursos e dividir para que possamos usar muito mais o que temos. Então pegamos o hipervisor e fazemos uma Máquina 1, Máquina 2, Máquina 3, assim, estamos criando setores de trabalho diferentes, fazendo com que nosso único servidor  pareça ser muitas máquinas diferentes.**

**Com os containers o isolamento é do processo, exemplo de quando executamos aplicativos em nossos computadores, eles são executados no mesmo ambiente, eles são mais rápidos e leves. Os containers nos permitem fazer, o compartilhamento do mesmo sistema operacional, onde estão compartilhando o mesmo kernel, mas está aparecendo para cada container como se tivesse seu próprio sistema operacional.**
