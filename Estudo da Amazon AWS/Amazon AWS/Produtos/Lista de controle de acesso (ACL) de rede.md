É um **firewall virtual** que **controla o tráfego de entrada e saída** no nível de sub-rede.

 🗒️ A filtragem de pacotes [[STATELESS]]

Elas **não** se registram os **históricos de entrada e de saída**. Eles verificam constantemente se pacotes estão na **lista permitida** quando pacotes entrar em sub-rede.

![[Pasted image 20230819173255.png]]
### ***Grupos de segurança**

É um **firewall virtual** que **controla o tráfego de entrada e saída** no nível de sub-rede. Por **padrão**, um grupo de segurança **nega todo o tráfego de entrada** e **permite todo o tráfego de saída.** Pode configurar e **personalizar regras**. Geralmente grupo de segurança está em **dentro de sub-rede** e verificar **o tráfego de instâncias**.

 🛡️ A filtragem de pacotes [[STATEFUL]]

Elas se registram os **históricos de entrada e de saída**. Eles permitem o tráfego se anteriormente pacote foi autorizada de entrar ou sair.
![[Pasted image 20230819173314.png]]

![[Pasted image 20230819173324.png]]