```markdown
# Meu Projeto com PlantUML

Este projeto utiliza o PlantUML para gerar diagramas a partir de arquivos `.wsd`.

## Instalação

### Requisitos

- Java JDK 8 ou superior
- Graphviz (opcional, mas recomendado)

### 1. Instalar o Java

Para instalar o Java:

#### Ubuntu

```bash
sudo apt update
sudo apt install default-jdk
```

#### macOS (usando Homebrew)

```bash
brew install openjdk
```

#### Windows

Baixe o JDK do [site oficial](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) e siga as instruções.

### 2. Baixar o PlantUML

Baixe o arquivo `plantuml.jar` do [site oficial](https://plantuml.com/download) e coloque em uma pasta, por exemplo, `~/plantuml`.

### 3. (Opcional) Instalar o Graphviz

Para instalar o Graphviz:

#### Ubuntu

```bash
sudo apt install graphviz
```

#### macOS

```bash
brew install graphviz
```

#### Windows

Baixe o instalador do [site do Graphviz](https://graphviz.gitlab.io/_pages/Download/Download.html) e siga as instruções.

### 4. Executar o PlantUML

Para gerar um diagrama a partir de um arquivo `.wsd`, use o seguinte comando no terminal:

```bash
java -jar ~/plantuml/plantuml.jar seu_diagrama.wsd
```

## Uso no Visual Studio Code

1. Instale a extensão "PlantUML" no VSCode.
2. Crie um arquivo `.wsd` e escreva seu diagrama.
3. Use `Alt+D` para visualizar o diagrama.

## Salvar
Como arquivo `exemplo.wsd` e execute:

```bash
java -jar ~/plantuml/plantuml.jar exemplo.wsd
```

Isso gerará um arquivo PNG com o diagrama.
```

ou

comando Alt + D.
