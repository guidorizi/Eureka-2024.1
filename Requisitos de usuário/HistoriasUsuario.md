# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white" >
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como um Coordenador, quero me registrar na plataforma, para que eu possa começar a postar eventos e atividades. </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li> O coordenador deve poder se registrar com login e senha.</li><li>O sistema deve validar a identidade do coordenador através de um processo de verificação.</li><li>Após a verificação, o coordenador deve ter acesso à funcionalidade de postagem de eventos.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"> Eu,como um Administrador,quero revisar e aprovar ou rejeitar eventos submetidos, para garantir que apenas conteúdos apropriados sejam publicados.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O administrador deve ter acesso a uma lista de eventos pendentes de aprovação.</li><li>O administrador deve poder visualizar todos os detalhes do evento e aprová-lo ou rejeitá-lo.</li><li>O sistema deve notificar o coordenador sobre a decisão (aprovação ou rejeição) e fornecer feedback se necessário.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF05</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como um Usuário regular,quero poder visualizar os anúncios de eventos e atividades com suas informações.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O usuário deve poder acessar uma página com uma lista de eventos.</li><li>Cada evento na lista deve exibir o título, descrição, horário e local.</li><li>O usuário deve ter a opção de filtrar ou pesquisar eventos por data, tipo ou palavra-chave.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04</td>
        </tr>
                 <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como um Usuário regular, quero receber notificações sobre novos eventos,para que eu possa estar atualizado sobre as novidades e participar dos eventos de meu interesse.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O sistema deve enviar notificações por e-mail ou mensagem interna quando novos eventos forem adicionados.</li><li> O usuário deve poder configurar suas preferências de notificação.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Baixa</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
                        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como um Usuário regular, quero atualizar minhas informações pessoais e de login,para que meus dados estejam sempre corretos e eu possa acessar minha conta sem problemas.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O usuário deve ter acesso a uma seção de perfil onde possa atualizar informações pessoais e detalhes de login.</li><li>O sistema deve validar as mudanças e atualizar as informações no banco de dados.</li><li>O usuário deve receber uma confirmação de que as alterações foram salvas com sucesso.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07</td>
        </tr>
           <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como um Administrador, quero gerenciar os usuários da plataforma,para garantir que todos os usuários estejam devidamente cadastrados e possam usar a plataforma conforme as políticas estabelecidas.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O administrador deve ter a capacidade de visualizar uma lista de todos os usuários da plataforma.</li><li>O administrador deve poder editar informações dos usuários e desativar contas se necessário.</li><li>O sistema deve permitir ao administrador monitorar atividades e resolver problemas relacionados aos usuários.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06</td>
                 </tr>
           <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como um Administrador, quero radicionar, editar e remover coordenadores de projetos,para que eu possa gerenciar quem tem permissão para postar eventos e atividades na plataforma.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O administrador deve poder adicionar novos coordenadores com login e senha.</li><li> O administrador deve poder editar informações dos coordenadores existentes.</li><li>O administrador deve poder remover coordenadores da plataforma se necessário.</li><li>O sistema deve atualizar as permissões e acessar os dados conforme as mudanças feitas.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF08</td>
                 </tr>
           <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como um Coordenador, quero cadastrar eventos e atividades na plataforma,para que os usuários possam visualizar e se inscrever nos eventos que estou promovendo.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O coordenador deve ter acesso a um formulário para inserir detalhes do evento (título, descrição, horário, local).</li><li>O coordenador deve poder submeter o evento para aprovação.</li><li>O evento deve ser visível para aprovação dos administradores antes de ser publicado na plataforma.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
</table>

<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>
