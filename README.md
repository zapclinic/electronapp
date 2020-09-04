# electronapp

Ambiente de versões do aplicativo zapclinic offline


# Publicar Lançamento
Primeiramento será precisa alterar o campo versão do arquivo package.json do projeto (zapclinic).
Então para que a nova versão seja criada e publicada no seu repositório de versões (https://github.com/zapclinic/electronapp) execute o comando:
´´´
yarn electron:publishWin
´´´
Após o termino processo anterior, abra seu repositório no GitHub (https://github.com/zapclinic/electronapp) e clique na guia releases. Você deve ver sua nova versão com "draft" com todos os binários incluídos. Torne essa versão em "Release" para que os usuários possam atualizá-la.

# Verifique se há atualizações
Instale seu aplicativo e execute-o. Você não receberá uma notificação de atualização ainda, porque esta com a versão mais recente. Você terá que publicar uma nova versão alterando o campo de versão em seu package.json e então publica-la (Seguindo o passos anteriores). Agora, seu aplicativo antigo deve fornecer uma notificação de atualização.
