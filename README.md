# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 24/04/2023
Empresa: Abstergo Industries 
Responsável: Emerson Pereira Ramos

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Emerson Pereira Ramos. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
- CloudWatch, é necessário criar uma política do AWS Identity and Access Management (IAM) e anexá-la ao usuário, grupo ou função. Para obter mais informações sobre usuários, grupos e funções, consulte Identidades do IAM (usuários, grupos de usuários e perfis). A política do IAM define as permissões do usuário.

Medida 2: 
- Habilitando Autenticação multifator.
Quando você habilita a autenticação multifator (MFA), os usuários devem fazer login no portal de AWS acesso com o nome de usuário e senha. Esse é o primeiro fator, algo que eles sabem. Os usuários também devem fazer login com um código ou uma chave de segurança. Esse é o segundo fator, algo que eles têm ou algo que são. O segundo fator pode ser um código de autenticação gerado pelo dispositivo móvel ou, alternativamente, ao tocar em uma chave de segurança conectada ao computador. Juntos, esses vários fatores fornecem maior segurança ao impedir o acesso não autorizado aos seus AWS recursos, a menos que um desafio válido de MFA tenha sido concluído com êxito. Cada usuário pode registrar até oito dispositivos de MFA.

Medida 3: 
- O Audit Manager automatiza a coleta de evidências para que você possa avaliar mais facilmente se suas políticas, procedimentos e atividades, também conhecidos como controles, estão funcionando de modo eficaz. Quando é hora de uma auditoria, o Audit Manager ajuda você a gerenciar as revisões de seus controles pelas partes interessadas. Isso significa que você pode criar relatórios prontos para auditoria com muito menos esforço manual.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado elevar o nivel de segurança de suas aplicações, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Responsável pelo Projeto:
Emerson Pereira ramos
