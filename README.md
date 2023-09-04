<head><h1>Requisitos Funcionais (RF)</h1></head>

<h3>RF001 – Cadastrar pacientes</h3>
1. RF001.1 - O sistema deve coletar informações pessoais das gestantes, incluindo nome, idade, endereço, telefone de contato, e outras informações relevantes.
2. RF001.2 - O sistema deve permitir o registro de informações médicas, como histórico médico, data de última menstruação, histórico de gestações anteriores, entre outros.

**RF002 – Cadastrar usuários**
1. RF002.1 - O sistema deve permitir o cadastro de profissionais da área da saúde com informações como nome, especialização, número de registro profissional, e dados de contato.
2. RF002.2 - Deve ser possível atribuir níveis de acesso aos usuários, como administrador, médico, enfermeiro, etc.

**RF003 – Consultar pacientes**
1. RF003.1 - O sistema deve oferecer a capacidade de pesquisa de pacientes com base em critérios como nome.
obs:filtros com provável utilidade relevantes como idade, tempo de de gestação, entre outros

**RF004 – Exibir dados da paciente**
1. RF004.1 - O sistema deve calcular e exibir a idade da gestante com base na data de nascimento informada.
2. RF004.2 - O sistema deve calcular e exibir o grau de risco da gestante com base em informações médicas.
3. RF004.3 - O sistema deve calcular e exibir a provável data de parto com base nas informações médicas.
4. RF004.4 - O sistema deve exibir a data do último atendimento da gestante.
5. RF004.5 - O sistema deve exibir a região de residência da gestante com base nas informações cadastradas.
6. RF004.6 - O sistema deve buscar os dados existentes no banco de dados da prefeitura e nas planilhas de controle para preencher as informações da gestante.

**RF005 – Exibir microáreas**
1. RF005.1 - O sistema deve exibir as microáreas geográficas onde as gestantes residem.

**RF006 – Exibir mini mapa**
1. RF006.1 - O sistema deve incluir um componente de mini mapa que pode mostrar as delimitações das microáreas geográficas.

**RF007 – Enviar alerta**
1. RF007.1 - O sistema deve monitorar o cumprimento dos requisitos governamentais (pré-natal, dentista, teste rápido) pelas gestantes.
2. RF007.2 - O sistema deve ser capaz de enviar alertas automáticos quando as gestantes não atenderem a esses requisitos.
3. RF007.3 - O sistema deve calcular e exibir uma porcentagem de adesão das gestantes aos requisitos governamentais.

**RF008 – Emitir relatório**
1. RF008.1 - O sistema deve gerar relatórios contendo informações sobre o percentual de adesão das gestantes aos requisitos governamentais.

<head><h1>Requisitos Não Funcionais (RNF)</h1></head>

**RNF001 – Responsividade (Usabilidade)**
1. RNF001.1 - O sistema deve ser capaz de se adaptar a diferentes tamanhos de tela, garantindo uma experiência de usuário adequada em dispositivos móveis, tablets e desktops.

**RNF002 – Compatibilidade de navegadores**
1. RNF002.1 - O sistema deve ser compatível com os principais navegadores da web, como Chrome, Internet Explorer e Opera.

**RNF003 – Segurança**
1. RNF003.1 - O sistema deve garantir a segurança dos dados médicos, localização e informações pessoais dos pacientes, implementando medidas como controle de acesso e auditoria de registros.
