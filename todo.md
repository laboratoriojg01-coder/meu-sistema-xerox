# Sistema JG Xerox - TODO

## Funcionalidades Principais

### Backend & Banco de Dados
- [x] Estender schema com tabela de registros
- [x] Implementar funções de banco de dados (CRUD)
- [x] Criar rotas tRPC protegidas (list, create, update, delete, deleteAll)
- [x] Testes unitários para rotas

### Frontend - Estrutura
- [x] Criar página Dashboard com 4 abas
- [x] Implementar navegação por Tabs
- [x] Configurar layout responsivo

### Aba 1: Cadastro
- [x] Formulário com 10 campos (Data, Hora, Nome, Turma, Folhas, Xérox, Equipamento, Controle TV, Cabo, Mês/Ano)
- [x] Validação de campos obrigatórios
- [x] Modo de edição de registros existentes
- [x] Botão "Limpar" para resetar formulário
- [x] Botão "Salvar/Atualizar Registro"

### Aba 2: Registros
- [x] Tabela com todos os registros
- [x] Botões de edição por registro
- [x] Botões de exclusão por registro
- [x] Botão "Exportar CSV"
- [x] Botão "Zerar Registros" com confirmação
- [x] Busca e filtros (pronto para expansão)

### Aba 3: Resumo
- [x] Cards coloridos com totais (Registros, Folhas, Xérox)
- [x] Estatísticas adicionais (médias, razões)
- [x] Botão "Baixar PDF"
- [x] Botão "Baixar DOCX"

### Aba 4: Análise
- [x] Gráfico de barras (registros por pessoa)
- [x] Gráfico de pizza (distribuição por turma)
- [x] Visualizações interativas com Recharts

### Geração de Relatórios
- [x] Função generatePDFReport()
- [x] Função generateDOCXReport()
- [x] Função generateReportHTML()

### Design & UX
- [x] Paleta de cores (azul/índigo com gradientes)
- [x] Cards com sombras
- [x] Interface responsiva
- [x] Feedback visual com toasts (Sonner)
- [x] Header com logo e botão logout
- [x] Animações suaves

### Autenticação
- [x] Login OAuth integrado
- [x] Logout com limpeza de sessão
- [x] Proteção de rotas
- [x] Contexto de usuário


## Melhorias Solicitadas

### Calendário na Aba Registros
- [x] Implementar calendário para filtrar registros por dia
- [x] Adicionar filtro por semana
- [x] Adicionar filtro por mês
- [x] Botões para download PDF/DOCX dos registros filtrados

### Resumo em Tempo Real
- [x] Exibir os 5 últimos registros na aba Cadastro
- [x] Atualizar resumo em tempo real ao criar novo registro
- [x] Design com cards mostrando informações principais


### Busca por Nome
- [x] Implementar campo de busca por nome na aba Registros
- [x] Filtrar registros em tempo real conforme digita
- [x] Combinar filtro de nome com filtros de período (dia/semana/mês)


### Filtro por Turma
- [x] Implementar dropdown/select para filtrar por turma
- [x] Extrair lista única de turmas dos registros
- [x] Filtrar registros em tempo real ao selecionar turma
- [x] Combinar filtro de turma com busca por nome e filtros de período


### Exportação para Excel
- [x] Instalar biblioteca xlsx (excel)
- [x] Criar função generateExcelReport() com abas por turma
- [x] Adicionar botão "Exportar Excel" na aba Registros
- [x] Organizar dados com cabeçalhos e formatação
- [x] Incluir resumo geral em aba separada


### Paginação na Tabela de Registros
- [ ] Adicionar estado para página atual e registros por página
- [ ] Implementar lógica de cálculo de páginas
- [ ] Criar componente de navegação de paginação
- [ ] Adicionar dropdown para selecionar registros por página (10, 25, 50, 100)
- [ ] Indicador de registros sendo exibidos
- [ ] Manter filtros ao navegar entre páginas
