#h3 

É um serviço que permite gerenciar o acesso aos recursos da AWS de forma segura. Com o IAM, você pode criar e gerenciar usuários, grupos, papéis e políticas que controlam quais ações podem ser realizadas em quais recursos. O IAM também oferece recursos como autenticação multifator, rotação de credenciais e integração com outros serviços da AWS e sistemas externos.

 👤 **Usuário-raiz da conta AWS**
É acessado ao entrar com o endereço de e-mail e a senha usados para criar a conta AWS. Tem acesso a todos serviços e permissão total. Não é recomendado para rotina diária.

 👥 **Políticas do IAM**
Permitem que personalize os níveis de acesso dos usuários aos recursos.

 👥 **Grupos do IAM**
São coleções de usuários do IAM que compartilham as mesmas permissões. Você pode usar grupos do IAM para gerenciar as permissões de vários usuários de forma eficiente e consistente. Por exemplo, você pode criar um grupo do IAM chamado "Administradores" e conceder a ele permissões de acesso total aos recursos da sua conta. Em seguida, você pode adicionar ou remover usuários desse grupo conforme necessário, sem precisar modificar as permissões individuais de cada usuário.

 🔑 **Funções do IAM**
É uma identidade que pode assumir para obter acesso temporário a permissões. Quando recebe nova uma função, automaticamente abandona todas as permissões anteriores que tinha.

