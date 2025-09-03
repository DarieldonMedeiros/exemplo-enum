# Exemplo de Enum - Estados Brasileiros

Este projeto demonstra o uso de **Enums** em Java através de um exemplo prático que representa estados brasileiros com suas respectivas informações do IBGE.

## 📋 Descrição

O projeto implementa um sistema simples que utiliza a funcionalidade de **Enum** do Java para representar estados brasileiros, incluindo suas siglas, nomes completos e códigos IBGE. Este é um exemplo educacional que mostra como trabalhar com enums de forma eficiente e organizada.

## 🏗️ Estrutura do Projeto

```bash
exemplo-enum/
├── src/
│   ├── EstadoBrasileiro.java    # Enum com os estados brasileiros
│   └── SistemaIBGE.java         # Classe principal com exemplos de uso
├── out/                         # Arquivos compilados (.class)
├── .idea/                       # Configurações do IntelliJ IDEA
├── exemplo-enum.iml            # Arquivo de módulo do IntelliJ
└── .gitignore                  # Arquivos ignorados pelo Git
```

## 🔧 Componentes

### EstadoBrasileiro.java

Enum que define os estados brasileiros com as seguintes propriedades:

- **Sigla**: Código de duas letras do estado (ex: SP, RJ)
- **Nome**: Nome completo do estado (ex: São Paulo, Rio de Janeiro)
- **IBGE**: Código numérico do IBGE (ex: 11, 12)

**Estados incluídos:**

- São Paulo (SP) - Código IBGE: 11
- Rio de Janeiro (RJ) - Código IBGE: 12
- Piauí (PI) - Código IBGE: 13
- Maranhão (MA) - Código IBGE: 14
- Ceará (CE) - Código IBGE: 15

**Métodos disponíveis:**

- `getSigla()`: Retorna a sigla do estado
- `getNome()`: Retorna o nome completo do estado
- `getIbge()`: Retorna o código IBGE
- `getNomeMaiusculo()`: Retorna o nome em maiúsculas

### SistemaIBGE.java

Classe principal que demonstra o uso do enum `EstadoBrasileiro`:

1. **Lista todos os estados**: Itera sobre todos os valores do enum e exibe sigla e nome
2. **Exemplo específico**: Demonstra o uso de um estado específico (Piauí) mostrando:
   - Nome completo
   - Sigla
   - Nome em maiúsculas

## 🚀 Como Executar

### Pré-requisitos

- Java JDK 8 ou superior
- IDE compatível (IntelliJ IDEA, Eclipse, VS Code, etc.)

## 📊 Saída Esperada

```bash
SP - São Paulo
RJ - Rio de Janeiro
PI - Piauí
MA - Maranhão
CE - Ceará

Piauí
PI
PIAUÍ
```

## 🎯 Conceitos Demonstrados

Este projeto exemplifica os seguintes conceitos de Java:

- **Enum**: Definição e uso de enums
- **Construtor de Enum**: Como definir construtores para enums
- **Métodos em Enum**: Implementação de métodos personalizados
- **Iteração sobre Enum**: Uso de `values()` para percorrer todos os valores
- **Encapsulamento**: Uso de campos privados e métodos getters
- **Imutabilidade**: Uso de `final` para garantir que os valores não sejam alterados

## 🔍 Funcionalidades

- ✅ Listagem de todos os estados cadastrados
- ✅ Acesso individual às propriedades de cada estado
- ✅ Formatação de dados (nome em maiúsculas)
- ✅ Códigos IBGE para integração com sistemas governamentais

## 🛠️ Possíveis Melhorias

- Adicionar mais estados brasileiros
- Implementar busca por sigla ou código IBGE
- Adicionar informações como região, população, etc.
- Criar métodos de validação
- Implementar serialização/deserialização

## 📚 Recursos de Aprendizado

Este projeto é ideal para:

- Estudantes aprendendo Java
- Desenvolvedores que querem entender enums
- Projetos que precisam trabalhar com dados geográficos do Brasil
- Exemplos de boas práticas em orientação a objetos

## 📄 Licença

Este projeto é de uso educacional e pode ser utilizado livremente para fins de aprendizado.

---

**Desenvolvido como exemplo educacional para demonstrar o uso de Enums em Java.**
