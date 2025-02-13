# PDF Snap Converter

## Overview
PDF Snap Converter is a desktop application built with Java Swing that allows you to convert PDF files into high-quality PNG images. It provides an intuitive interface for selecting a PDF file and generating images for each page with 300 DPI resolution.

## Features
- Convert PDF to PNG with high quality (300 DPI)
- User-friendly graphical interface (Java Swing)
- Supports multiple pages in a single PDF
- Generates PNG images in the same directory as the original PDF
- Built using Apache PDFBox and Lombok
- Packaged as an executable `.exe` for Windows users

## Requirements
- Java 21 or later
- Maven (for building the project)
- Windows (for `.exe` generation, optional)

## Installation and Usage

### 1. Clone the Repository
```sh
git clone https://github.com/rafaelvulner/pdf-snap-converter.git
cd pdf-snap-converter
```

### 2. Build the Project
```sh
mvn clean package
```

### 3. Run the Application
```sh
java -jar target/pdf-snap-converter-1.0-SNAPSHOT.jar
```

### 4. Generate Executable (.exe) for Windows
```sh
mvn jpackage:jpackage
```
The `.exe` file will be generated in `target/jpackage/PDF Snap Converter/PDF Snap Converter.exe`.

## Dependencies
- **Apache PDFBox** (3.0.3) – For PDF processing
- **Lombok** (1.18.36) – Reduces boilerplate code
- **Maven Compiler Plugin** – Ensures compatibility with Java 21
- **JPackage Plugin** – Generates a native Windows executable

## License
This project is licensed under the MIT License.

---

# PDF Snap Converter (Português - Brasil)

## Visão Geral
O PDF Snap Converter é um aplicativo desktop desenvolvido com Java Swing que permite converter arquivos PDF em imagens PNG de alta qualidade. Ele oferece uma interface intuitiva para selecionar um arquivo PDF e gerar imagens para cada página com resolução de 300 DPI.

## Recursos
- Converte PDF para PNG com alta qualidade (300 DPI)
- Interface gráfica amigável (Java Swing)
- Suporte para múltiplas páginas em um único PDF
- Gera imagens PNG no mesmo diretório do PDF original
- Construído com Apache PDFBox e Lombok
- Empacotado como um executável `.exe` para usuários Windows

## Requisitos
- Java 21 ou superior
- Maven (para compilar o projeto)
- Windows (para geração do `.exe`, opcional)

## Instalação e Uso

### 1. Clonar o Repositório
```sh
git clone https://github.com/rafaelvulner/pdf-snap-converter.git
cd pdf-snap-converter
```

### 2. Compilar o Projeto
```sh
mvn clean package
```

### 3. Executar o Aplicativo
```sh
java -jar target/pdf-snap-converter-1.0-SNAPSHOT.jar
```

### 4. Gerar Executável (.exe) para Windows
```sh
mvn jpackage:jpackage
```
O arquivo `.exe` será gerado em `target/jpackage/PDF Snap Converter/PDF Snap Converter.exe`.

## Dependências
- **Apache PDFBox** (3.0.3) – Para manipulação de PDFs
- **Lombok** (1.18.36) – Redução de código repetitivo
- **Maven Compiler Plugin** – Garante compatibilidade com Java 21
- **JPackage Plugin** – Gera um executável nativo para Windows

## Licença
Este projeto está licenciado sob a Licença MIT.

