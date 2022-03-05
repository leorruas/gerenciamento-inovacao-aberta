# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>



## Personas

<table>
  <tr>
    <th>Nome</th>
    <th>Descrição</th>
    <th>Aplicativos</th>
    <th>Motivações</th>
    <th>Frustrações</th>
    <th>Hobbies, História</th>
  </tr>
  <tr>
    <td>Robson Santos</td>
    <td>
      <ul>
        <li>48 anos</li>
        <li>Executivo de TI</li>
        <li>Capital, Rio de Janeiro</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Linkedin</li>
        <li>Uol</li>
        <li>WhatsApp</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Carnaval</li>
        <li>Inovação</li>
        <li>Tecnologia</li>
      </ul>
    </td>
    <td>
      <li>Não Encontrar startups que soluciona o problema da minha empresa</li>
      <li>Dificuldade de achar profissionais de tecnologia qualificados</li>
    </td>
    <td>
      <li>Tocar instrumentos de percussão</li>
      <li>Assistir documentários</li>
      <li>Estudar sobre tecnologia</li>
    </td>
  </tr>
  <tr>
    <td>Caio Gomes</td>
    <td>
      <ul>
        <li>25 anos</li>
        <li>Desenvolvedor de Software</li>
        <li>Curitiba, Paraná</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Stack Overflow</li>
        <li>Reddit</li>
        <li>Telegram</li>
        <li>Twitter</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Tecnologia</li>
        <li>Programação</li>
        <li>Bitcoin</li>
      </ul>
    </td>
    <td>
      <li>Dificuldade para achar parcerias em desenvolvimento de produtos de tecnologia</li>
      <li>Não ter seu próprio negócio</li>
    </td>
    <td>
      <li>Ler sobre tecnologia</li>
      <li>Jogar Video-Game</li>
      <li>Aprender novas linguagens de programação</li>
    </td>
  </tr>
  <tr>
    <td>Isabel Duarte</td>
    <td>
      <ul>
        <li>37 anos</li>
        <li>Empresária</li>
        <li>Pipa, Rio Grande do Norte</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Linkedin</li>
        <li>Instagram</li>
        <li>G1</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Negócios</li>
        <li>Marketing</li>
        <li>Luiza Trajano</li>
      </ul>
    </td>
    <td>
      <li>Não encontrar um ambiente de negócio que fomente a inovação</li>
      <li>Não conseguir crescer o networking</li>
    </td>
    <td>
      <li>Caminhar na praia</li>
      <li>Festa com amigos</li>
      <li>Tomar um vinho lendo um livro</li>
    </td>
  </tr>
</table>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Administrador       | ter acesso a todos as empresas que se cadastraram no site           |  sugerir conexões entre elas |
|Usuário             | procurar empresas                 | conhecer e entrar em contato |
|Usuário             | saber se o serviço das empresas listadas é pago |  alocar recurso para pagar|
|Usuário             | saber a que distância estão os empreendimentos listados | programar uma logística de acesso |
|Usuário             | filtrar os empreendimentos por nichos de mercado | escolher os que oferecem os serviços que melhor lhe atendem | 
|Usuário             | ter espaço de fórum | debater com parceiros sobre dificuldades e procurar soluções em conjunto |
|Usuário             | encontrar espaços de lazer próximos em que possa encontrar com profissionais desses empreendimentos | fazer networking |



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Criar sistema de relações (adicionar/seguir) | ALTA | 
|RF-002| Listar interesses na rede   | ALTA |
|RF-003| Permitir espaço de promoção do usuário por meio de texto e imagem   | ALTA |
|RF-004| Georreferencar o local da empresa  | ALTA |
|RF-005| Criar espaço de fórum para os usuários  | BAIXA |
|RF-006| Permitir ao usuário que liste suas áreas de atuação  | ALTA |
|RF-007| Permitir ao usuário buscar por outros usuários  | ALTA |
|RF-007| Permitir ao usuário buscar utilizando critérios, como distância, serviços, interesses  | ALTA |
|RF-008| Sugerir conexões ao usuário com base nos dados  | BAIXA |
|RF-009| Permitir ao usuário que liste serviços pagos e não-pagos  | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em qualquer dispositivo | ALTA | 
|RNF-002| A aplicação deve ter uma interface e copy amigável (simpática) |  MÉDIA | 
|RNF-003| A plataforma deve oferecer segurança no armazenamento de dados do usuário |  ALTA | 
|RNF-004| Necessário verificação do dono do negócio |  ALTA | 




## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

