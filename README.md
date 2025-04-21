# Sage Extensibilidade
Repositório dos projetos de extensibilidade do software Sage

## Extensibilidade - Como fazer

1 - Configuração no Sage 50 Faturação  
2 - Desenvolvimento da Dll

### 1. Configuração no Sage 50 Faturação

**Menu Personalização** --> Parametrizações Funcionais --> Integração de dados --> Extensibilidade --> <ins>Adicionar extensibilidade  

Nesta área poderá adicionar o projeto ou os vários projetos de extensibilidade pretendidos. Os projetos serão executados pela ordem com que são inseridos nos Parâmetros.

• **Descrição:** [Descrição do(s) projeto(s)]  
• **Ponto de entrada para a classe IsageExtender:** [Indicação da classe] As Dll deverão ser copiadas para a pasta COMMONFILES\Sage\2070\50c2018\Extensibility\ do disco local e registadas com linha de comandos elevada  
• **Carrega o módulo de extensibilidade em:** BackOffice. Aquando da gravação dos parâmetros deverá reiniciar a aplicação.

