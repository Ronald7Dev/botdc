# Política de Privacidade — Discord Perm Tool

Última atualização: 25 de setembro de 2026

## Dados acessados
O bot **não usa nenhum Privileged Intent**. Ele não lê o conteúdo de mensagens, não acessa a lista de membros e não monitora presença.

Para funcionar, ele acessa apenas:
- ID do servidor;
- IDs e nomes de canais, categorias e cargos;
- As permissões (overwrites) configuradas em cada canal;
- O ID do usuário que executa um comando slash, apenas durante a execução daquele comando.

## Dados armazenados
Somente o comando `/perm backup` salva dados. Ele gera um arquivo JSON com as permissões de canais do servidor (IDs de canais, cargos e suas permissões). Esse arquivo:
- fica salvo localmente na pasta `backups/` da máquina onde o bot é executado;
- é enviado no próprio canal onde o comando foi usado.

Nenhum dado de usuário é armazenado. Nada é enviado para servidores externos, bancos de dados ou terceiros.

## Compartilhamento
Os dados não são vendidos, compartilhados nem usados para publicidade ou análise.

## Exclusão de dados
Arquivos de backup podem ser apagados a qualquer momento pelo administrador que executa o bot, removendo-os da pasta `backups/`. Você também pode pedir a exclusão pelo contato abaixo.

## Terceiros
O bot funciona dentro da plataforma Discord, que tem sua própria [Política de Privacidade](https://discord.com/privacy).

## LGPD
O tratamento de dados segue a Lei Geral de Proteção de Dados (Lei nº 13.709/2018).

## Contato
Abra uma issue em https://github.com/Ronald7Dev/botdc/issues ou fale com **SEU_USUARIO_DISCORD**.