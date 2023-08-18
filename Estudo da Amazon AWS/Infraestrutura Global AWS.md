### Região
Uma região é a disponibilização de uma coleção de recursos AWS em uma localização geográfica, sendo ele composto por **um conjunto de zonas de disponibilidade.**

![[Pasted image 20230818201855.png]]

### Zona de disponibilidade
Uma zona de disponibilidade é **um ou mais data centers** que estão na **mesma região**, porém separados a **quilômetros de distância com energia, rede e conectividade redundantes**.
![[Pasted image 20230818202048.png]]
> [!🎯 Considere os quatro fatores de negócio a seguir] 
> - **Conformidade:** Governança de dados e requisitos legais
> - **Proximidade:** Latência entre servidor e cliente
> - **Serviços disponíveis em uma região:** Amazon Braket (Computação quântica) não está disponível em todas as regiões
> - **Definição de preços:** Estrutura tributária  

### Ponto de presença (Edge Locations)
Um ponto de presença é **uma infraestrutura de servidores**, localizado próximo de uma zona de disponibilidade, que armazena os dados mais solicitados no **cache**, para entregar com **menor latência** uma requisição de consulta.
![[Pasted image 20230818202319.png]]




