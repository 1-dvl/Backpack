# Especificação do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 01: Usuário da Plataforma </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Perfil principal da aplicação, reunindo em um mesmo tipo de usuário os comportamentos de descoberta, avaliação, organização e participação em discussões sobre jogos, séries e filmes.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1. Personalizar o perfil escolhendo quais categorias deseja acompanhar.
2. Responder perguntas iniciais para direcionar recomendações.
3. Visualizar conteúdos recomendados ou salvos com notas visíveis.
4. Avaliar conteúdos, comentar e criar tópicos por obra.
5. Acompanhar opiniões de amigos ou perfis relevantes.
6. Organizar listas pessoais e navegar em um feed complementar de descoberta.</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 02: Administrador/Moderador </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Perfil responsável por manter o catálogo organizado e preservar a qualidade das interações na plataforma.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1. Cadastrar e editar conteúdos do catálogo.
2. Moderar comentários e tópicos inadequados.
3. Gerenciar denúncias.
4. Manter a consistência das informações.</td>
</tr>
</tbody>
</table>

## Histórias de Usuários

|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE`                                   |PARA ... `PORQUE`                                                    |RESPONSÁVEL|PÁGINA                  |
|--------------------|-------------------------------------------------------------|---------------------------------------------------------------------|-----------|------------------------|
| Visitante          | criar uma conta na plataforma                               | personalizar minha experiência e salvar minhas preferências.        | Equipe    | Cadastro               |
| Usuário            | entrar e sair da plataforma com segurança                   | acessar meu perfil com praticidade e proteger minhas informações.   | Equipe    | Autenticação           |
| Usuário            | escolher quais tipos de conteúdo desejo acompanhar          | receber uma experiência mais alinhada ao que quero ver.             | Equipe    | Perfil / Onboarding    |
| Usuário            | responder perguntas iniciais sobre meus gostos              | refinar minhas recomendações desde o primeiro acesso.               | Equipe    | Perfil / Onboarding    |
| Usuário            | visualizar cards personalizados com imagem e nota geral     | decidir mais rápido o que assistir ou jogar.                        | Equipe    | Home / Conteúdos       |
| Usuário            | pesquisar títulos pelo nome                                 | encontrar um conteúdo específico com mais rapidez.                  | Equipe    | Busca                  |
| Usuário            | abrir a página detalhada de um conteúdo                     | ver informações, notas e discussões daquela obra.                   | Equipe    | Detalhe do Conteúdo    |
| Usuário            | seguir, bloquear, acompanhar, conversar com outros usuários | criar comunidades na aplicação.                                     | Equipe    | Interação              |
| Usuário            | atribuir nota aos conteúdos                                 | registrar minha opinião e contribuir para a avaliação coletiva.     | Equipe    | Detalhe do Conteúdo    |
| Usuário            | comentar e responder comentários nas páginas dos conteúdos  | participar de conversas sobre aquilo de que gosto.                  | Equipe    | Detalhe do Conteúdo    |
| Usuário            | destacar comentários e notas de amigos e perfis acompanhados| considerar opiniões mais próximas do meu gosto.                     | Equipe    | Detalhe do Conteúdo    |
| Usuário            | criar tópicos específicos por conteúdo                      | organizar discussões por teoria, dúvida ou opinião.                 | Equipe    | Detalhe do Conteúdo    |
| Usuário            | criar listas como “favoritos”, “quero ver” e “quero jogar”  | organizar meu consumo de entretenimento.                            | Equipe    | Listas                 |
| Usuário            | acessar aos conteúdos mais populares                        | ficar por dentro dos assuntos em alta.                              | Equipe    | Home / Conteúdos       |

## Requisitos do Projeto

### Requisitos Funcionais

|ID        | Descrição                                                                                          | Prioridade   |
|----------|----------------------------------------------------------------------------------------------------|--------------|
| RF-01    |  Permitir ao usuário criar uma conta.                                                              | ALTA         | 
| RF-02    |  Permitir ao usuário fazer login e logout.                                                         | ALTA         | 
| RF-03    |  Permitir ao usuário personalizar o perfil, escolhendo quais tipos de conteúdo deseja acompanhar.  | ALTA         | 
| RF-04    |  Permitir ao usuário responder a um questionário inicial de preferências.                          | ALTA         | 
| RF-05    |  Exibir na área principal conteúdos preferidos pelo usuário.                                       | ALTA         | 
| RF-06    |  Permitir realizar filtros.                                                                        | ALTA         | 
| RF-07    |  Exibir uma página detalhada para cada conteúdo.                                                   | ALTA         | 
| RF-08    |  Permitir ao usuário seguir interagir com outros usuários                                          | ALTA         | 
| RF-09    |  Permitir ao usuário atribuir nota a um conteúdo.                                                  | MÉDIA        | 
| RF-10    |  Permitir ao usuário comentar e responder comentários em páginas de conteúdos.                     | ALTA         | 
| RF-11    |  Destacar, na página do conteúdo, comentários e notas de amigos ou perfis acompanhados.            | MÉDIA        | 
| RF-12    |  Permitir a criação de fóruns para cada conteúdo.                                                  | MÉDIA        | 
| RF-13    |  Permitir a criação de listas pessoais.                                                            | ALTA         | 
| RF-14    |  Exibir tópico “em alta” na página principal.                                                      | MÉDIA        | 

**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais

|ID             | Descrição                                                                                                                                              | Prioridade   |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| RF-01         |  A aplicação deve estar disponível publicamente na Internet com disponibilidade mínima de 95% de uptime mensal.                                        | ALTA         | 
| RF-02         |  A aplicação deve ser responsiva, funcionando corretamente em dispositivos móveis, tablets e desktops, com suporte aos navegadores Google Chrome, Mozilla Firefox, Opera GX e Microsoft Edge nas duas versões mais recentes.                                                                                                                                              | ALTA         | 
| RF-03         |  As páginas principais da aplicação devem carregar em até 3 segundos em conexão banda larga residencial padrão.                                        | ALTA         | 
| RF-04         |  O sistema deve garantir segurança dos dados dos usuários, incluindo autenticação por login e senha criptografada e proteção das informações pessoais e preferências do usuário.                                                                                                                                                                                               | ALTA         | 
| RF-05         |  O código da aplicação deve seguir padrão de organização em componentes reutilizáveis e arquitetura que facilite a manutenção e evolução do sistema.   | ALTA         | 

**Prioridade: Alta / Média / Baixa. 

