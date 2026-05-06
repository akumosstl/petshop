# Graph Report - C:\Users\USER\projects\github\petshop  (2026-05-06)

## Corpus Check
- 103 files · ~40,798 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 661 nodes · 1017 edges · 61 communities detected
- Extraction: 60% EXTRACTED · 40% INFERRED · 0% AMBIGUOUS · INFERRED: 402 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 34|Community 34]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 36|Community 36]]
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Community 45|Community 45]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 47|Community 47]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Community 49|Community 49]]
- [[_COMMUNITY_Community 50|Community 50]]
- [[_COMMUNITY_Community 51|Community 51]]
- [[_COMMUNITY_Community 52|Community 52]]
- [[_COMMUNITY_Community 53|Community 53]]
- [[_COMMUNITY_Community 54|Community 54]]
- [[_COMMUNITY_Community 55|Community 55]]
- [[_COMMUNITY_Community 56|Community 56]]
- [[_COMMUNITY_Community 57|Community 57]]
- [[_COMMUNITY_Community 58|Community 58]]
- [[_COMMUNITY_Community 59|Community 59]]
- [[_COMMUNITY_Community 60|Community 60]]

## God Nodes (most connected - your core abstractions)
1. `Cliente` - 26 edges
2. `ClienteRequestDTO` - 21 edges
3. `DashboardController` - 20 edges
4. `DashboardService` - 20 edges
5. `FuncionarioRepository` - 17 edges
6. `Pet` - 16 edges
7. `useNotification()` - 16 edges
8. `PetResponseDTO` - 15 edges
9. `ClienteResponseDTO` - 14 edges
10. `Consulta` - 14 edges

## Surprising Connections (you probably didn't know these)
- `AuditoriaPage()` --calls--> `useNotification()`  [INFERRED]
  C:\Users\USER\projects\github\petshop\frontend\app\auditoria\page.js → C:\Users\USER\projects\github\petshop\frontend\contexts\NotificationContext.js
- `ClientesPage()` --calls--> `useNotification()`  [INFERRED]
  C:\Users\USER\projects\github\petshop\frontend\app\clientes\page.js → C:\Users\USER\projects\github\petshop\frontend\contexts\NotificationContext.js
- `ClientePerfil()` --calls--> `useNotification()`  [INFERRED]
  C:\Users\USER\projects\github\petshop\frontend\app\clientes\[cpf]\page.js → C:\Users\USER\projects\github\petshop\frontend\contexts\NotificationContext.js
- `ConsultasSQL()` --calls--> `useNotification()`  [INFERRED]
  C:\Users\USER\projects\github\petshop\frontend\app\consultas\page.js → C:\Users\USER\projects\github\petshop\frontend\contexts\NotificationContext.js
- `ConsultasServicosPage()` --calls--> `useNotification()`  [INFERRED]
  C:\Users\USER\projects\github\petshop\frontend\app\consultas-servicos\page.js → C:\Users\USER\projects\github\petshop\frontend\contexts\NotificationContext.js

## Communities

### Community 0 - "Community 0"
Cohesion: 0.06
Nodes (9): AtendenteResponseDTO(), Funcionario, FuncionarioRepository, FuncionarioService, ItemVendaRequestDTO, Venda, VendaRepository, VendaService (+1 more)

### Community 1 - "Community 1"
Cohesion: 0.1
Nodes (5): Cliente, ClienteRepository, ClienteRowMapper, ClienteService, VeterinarioResponseDTO()

### Community 2 - "Community 2"
Cohesion: 0.11
Nodes (4): ProdutoRepository, ProdutoRequestDTO, ProdutoResponseDTO, ProdutoService

### Community 3 - "Community 3"
Cohesion: 0.06
Nodes (18): ClienteModal(), FornecedorModal(), FuncionarioModal(), useNotification(), NotificationToast(), AuditoriaPage(), ClientePerfil(), ClientesPage() (+10 more)

### Community 4 - "Community 4"
Cohesion: 0.06
Nodes (4): DashboardController, PetController, ErrorDetails, RestExceptionHandler

### Community 5 - "Community 5"
Cohesion: 0.15
Nodes (3): Pet, PetRepository, PetService

### Community 6 - "Community 6"
Cohesion: 0.1
Nodes (4): Consulta, ConsultaRepository, ConsultaService, Exame

### Community 7 - "Community 7"
Cohesion: 0.19
Nodes (4): Fornecedor, FornecedorRepository, FornecedorRowMapper, FornecedorService

### Community 8 - "Community 8"
Cohesion: 0.09
Nodes (1): ClienteRequestDTO

### Community 9 - "Community 9"
Cohesion: 0.1
Nodes (1): DashboardService

### Community 10 - "Community 10"
Cohesion: 0.12
Nodes (2): ErrorResponse, FuncionarioController

### Community 11 - "Community 11"
Cohesion: 0.12
Nodes (1): PetResponseDTO

### Community 12 - "Community 12"
Cohesion: 0.25
Nodes (1): ClienteResponseDTO

### Community 13 - "Community 13"
Cohesion: 0.14
Nodes (1): ConsultaResponseDTO

### Community 14 - "Community 14"
Cohesion: 0.14
Nodes (1): PetRequestDTO

### Community 15 - "Community 15"
Cohesion: 0.14
Nodes (1): VendaResponseDTO

### Community 16 - "Community 16"
Cohesion: 0.2
Nodes (3): ConsultaController, ErrorResponse, ConsultaSqlRequestDTO

### Community 17 - "Community 17"
Cohesion: 0.17
Nodes (1): FuncionarioResponseDTO

### Community 18 - "Community 18"
Cohesion: 0.22
Nodes (2): ClienteController, ErrorResponse

### Community 19 - "Community 19"
Cohesion: 0.24
Nodes (2): ErrorResponse, FornecedorController

### Community 20 - "Community 20"
Cohesion: 0.2
Nodes (1): ConsultaRequestDTO

### Community 21 - "Community 21"
Cohesion: 0.2
Nodes (1): FuncionarioRequestDTO

### Community 22 - "Community 22"
Cohesion: 0.2
Nodes (1): VendaCompletaRequestDTO

### Community 23 - "Community 23"
Cohesion: 0.2
Nodes (1): VendaRequestDTO

### Community 24 - "Community 24"
Cohesion: 0.2
Nodes (5): Configuracoes(), Dashboard(), ThemeProvider(), useTheme(), useLocalStorage()

### Community 25 - "Community 25"
Cohesion: 0.25
Nodes (1): FornecedorRequestDTO

### Community 26 - "Community 26"
Cohesion: 0.25
Nodes (1): FornecedorResponseDTO

### Community 27 - "Community 27"
Cohesion: 0.29
Nodes (1): ProdutoController

### Community 28 - "Community 28"
Cohesion: 0.29
Nodes (1): ExameResponseDTO

### Community 29 - "Community 29"
Cohesion: 0.4
Nodes (2): ErrorResponse, VendaController

### Community 30 - "Community 30"
Cohesion: 0.67
Nodes (1): PetShopApplication

### Community 31 - "Community 31"
Cohesion: 0.67
Nodes (1): WebConfig

### Community 32 - "Community 32"
Cohesion: 0.67
Nodes (1): BusinessException

### Community 33 - "Community 33"
Cohesion: 0.67
Nodes (1): ResourceNotFoundException

### Community 34 - "Community 34"
Cohesion: 0.67
Nodes (1): Atendente

### Community 35 - "Community 35"
Cohesion: 0.67
Nodes (1): PetShopApplicationTests

### Community 36 - "Community 36"
Cohesion: 1.0
Nodes (1): ExameRequestDTO

### Community 37 - "Community 37"
Cohesion: 1.0
Nodes (1): Produto

### Community 38 - "Community 38"
Cohesion: 1.0
Nodes (0): 

### Community 39 - "Community 39"
Cohesion: 1.0
Nodes (0): 

### Community 40 - "Community 40"
Cohesion: 1.0
Nodes (0): 

### Community 41 - "Community 41"
Cohesion: 1.0
Nodes (0): 

### Community 42 - "Community 42"
Cohesion: 1.0
Nodes (0): 

### Community 43 - "Community 43"
Cohesion: 1.0
Nodes (0): 

### Community 44 - "Community 44"
Cohesion: 1.0
Nodes (0): 

### Community 45 - "Community 45"
Cohesion: 1.0
Nodes (0): 

### Community 46 - "Community 46"
Cohesion: 1.0
Nodes (0): 

### Community 47 - "Community 47"
Cohesion: 1.0
Nodes (0): 

### Community 48 - "Community 48"
Cohesion: 1.0
Nodes (0): 

### Community 49 - "Community 49"
Cohesion: 1.0
Nodes (0): 

### Community 50 - "Community 50"
Cohesion: 1.0
Nodes (0): 

### Community 51 - "Community 51"
Cohesion: 1.0
Nodes (0): 

### Community 52 - "Community 52"
Cohesion: 1.0
Nodes (0): 

### Community 53 - "Community 53"
Cohesion: 1.0
Nodes (0): 

### Community 54 - "Community 54"
Cohesion: 1.0
Nodes (0): 

### Community 55 - "Community 55"
Cohesion: 1.0
Nodes (0): 

### Community 56 - "Community 56"
Cohesion: 1.0
Nodes (0): 

### Community 57 - "Community 57"
Cohesion: 1.0
Nodes (0): 

### Community 58 - "Community 58"
Cohesion: 1.0
Nodes (0): 

### Community 59 - "Community 59"
Cohesion: 1.0
Nodes (0): 

### Community 60 - "Community 60"
Cohesion: 1.0
Nodes (0): 

## Knowledge Gaps
- **2 isolated node(s):** `ExameRequestDTO`, `Produto`
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 36`** (2 nodes): `ExameRequestDTO.java`, `ExameRequestDTO`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 37`** (2 nodes): `Produto.java`, `Produto`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 38`** (2 nodes): `layout.js`, `RootLayout()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 39`** (2 nodes): `page.js`, `GraficosEstaticos()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 40`** (2 nodes): `ImageModal.js`, `ImageModal()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 41`** (2 nodes): `PetModal.js`, `PetModal()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 42`** (2 nodes): `Sidebar.js`, `Sidebar()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 43`** (2 nodes): `ChartConfig.js`, `registerChartComponents()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 44`** (2 nodes): `ConsultasPorVetChart.js`, `ConsultasPorVetChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 45`** (2 nodes): `DashboardGlobalFilters.js`, `DashboardGlobalFilters()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 46`** (2 nodes): `FaturamentoAnualChart.js`, `FaturamentoAnualChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 47`** (2 nodes): `FaturamentoDiarioChart.js`, `FaturamentoDiarioChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 48`** (2 nodes): `FaturamentoMensalChart.js`, `FaturamentoMensalChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 49`** (2 nodes): `KpiCard.js`, `KpiCard()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 50`** (2 nodes): `NovosClientesChart.js`, `NovosClientesChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 51`** (2 nodes): `PetsPorIdadeChart.js`, `PetsPorIdadeChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 52`** (2 nodes): `ProdutosEncalhadosTable.js`, `ProdutosEncalhadosTable()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 53`** (2 nodes): `TopClientesChart.js`, `TopClientesChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 54`** (2 nodes): `TopProdutosChart.js`, `TopProdutosChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 55`** (2 nodes): `VendasPorAtendenteChart.js`, `VendasPorAtendenteChart()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 56`** (1 nodes): `AtendenteRequestDTO.java`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 57`** (1 nodes): `FuncionarioGeralResponseDTO.java`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 58`** (1 nodes): `VeterinarioRequestDTO.java`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 59`** (1 nodes): `eslint.config.mjs`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 60`** (1 nodes): `next.config.mjs`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `ConsultaService` connect `Community 6` to `Community 16`?**
  _High betweenness centrality (0.020) - this node is a cross-community bridge._
- **What connects `ExameRequestDTO`, `Produto` to the rest of the system?**
  _2 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.1 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.11 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._