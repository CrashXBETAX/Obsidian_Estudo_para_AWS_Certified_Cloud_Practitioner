### Monolítico
Os aplicativos são formados por vários componentes. Os componentes se comunicam entre si para transmitir dados, atender solicitações e manter o aplicativo em execução.
Nessa abordagem à arquitetura do aplicativo, se um único componente falhar, outros componentes falharão e possivelmente todo o aplicativo.

![[Pasted image 20230819171651.png]]

### Microsserviços
Neste caso, se um único componente falhar, os outros componentes continuarão funcionando porque estarão em comunicação uns com os outros. O acoplamento fraco evita a falha completa do aplicativo.
Ao projetar aplicativos na AWS, você pode adotar uma abordagem de microsserviços com serviços e componentes que cumprem funções diferentes. Dois serviços facilitam a integração de aplicativos: Amazon Simple Notification Service (Amazon SNS) e Amazon Simple Queue Service (Amazon SQS).
![[Pasted image 20230819171713.png]]
