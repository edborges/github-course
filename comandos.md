Comandos Git

O comando mkdir cria uma pasta.

O 'git diff' permite Verificar as modificações
antes de commitar. é muito importante, pois possibilita revisão.

O 'git checkout' mais nome do arquivo - serve para desfazer o comit quando as alterações ainda não foram comitadas.

O 'git reset' é de suma importância, e usado para voltar ao estados anteriores,
desfazendo o commit especificado.
Ele tem 3 opções:
'git reset --soft' que volta para o estado com as modificações em stage, pronto para comitar novamente;
'git reset --mixed' que volta para o estado com as modificações em modified, que precisará ser adicionada novamente antes de comitar;

'git reset --hard' que desfaz o comit e defaz as modificações.
