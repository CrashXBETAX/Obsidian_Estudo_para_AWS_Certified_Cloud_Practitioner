 📖 **S3 Standard**
- Projetado para dados acessados com frequência
- Armazena dados com um mínimo de três Zonas de Disponibilidade
É bom para diversos casos de uso, como sites

 💽 S3 **S**tandard-**I**nfrequent **A**cess **(S3 Standard-IA)**
- Ideal para dados com pouca frequência de acesso
- Semelhante ao S3 Standard, mas com um preço de armazenamento mais baixo e um preço de recuperação mais alto. 

 💽 S3 One Zone-**I**nfrequent **A**cess **(S3 One Zone-IA)**
- Armazena dados em uma única Zona de Disponibilidade
- Tem um preço de armazenamento menor do que o S3 Standard - IA 

 💽 **S3 Intelligent-Tiering**
- Ideal para dados com padrões de acesso desconhecido ou em alteração
- Requer uma pequena taxa mensal de monitoramento e automação por objeto
- Se você acessar um objeto no nível de acesso pouco frequente, o move automaticamente para S3 Standard, por exemplo. 

 💽 **S3 Glacier**
- Armazenamento de baixo custo projetado para arquivamento de dados
- Capaz de recuperar objetos em poucos minutos a horas. 

 💽 **S3 Glacier Deep Archive**
- Armazenamento de baixo custo projetado para arquivamento de dados
- Capaz de recuperar objetos em 12 horas. 