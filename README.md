![Mobile-Flutter: Flutter CI](capa.png)

# Flutter CI Alura - Sorteador de Amigo Secreto

[![Flutter](https://img.shields.io/badge/Flutter-3.0.5+-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.0.5+-0175C2?logo=dart)](https://dart.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Aplicativo Flutter de sorteio de amigo secreto com testes automatizados e integração contínua. Desenvolvido durante o curso **"Flutter: aplicando integração contínua (CI)"** da [Alura](https://www.alura.com.br/) no **BootCamp Santander de Desenvolvimento Mobile 2025**.

## 📱 Sobre o Projeto

Este projeto é uma aplicação mobile que permite realizar sorteios de amigo secreto de forma simples e organizada. O foco principal do desenvolvimento foi a implementação de **boas práticas de CI/CD**, incluindo testes automatizados, pipelines e controle de qualidade de código.

![GIF da aplicação em execução](sorteador.gif)

## ✨ Funcionalidades

- 🎲 **Sorteio de Amigo Secreto**: Insira os nomes dos participantes e realize o sorteio
- ✅ **Validação de Regras**: Garante que ninguém tire a si mesmo no sorteio
- 🎨 **Interface Intuitiva**: Design limpo e fácil de usar
- 🧪 **Testes Automatizados**: Cobertura de testes unitários e de integração
- 🔄 **Gerenciamento de Estado**: Implementado com BLoC/Cubit

## 🎯 Tópicos Abordados

Durante o desenvolvimento deste projeto, foram estudados e aplicados os seguintes conceitos:

- ✅ **Integração Contínua (CI)**
- ✅ **Pipelines de Build**
- ✅ **Testes Automatizados** (Unitários e de Integração)
- ✅ **BLoC Pattern** para gerenciamento de estado
- ✅ **Qualidade de Código**
- ✅ **Boas Práticas de Desenvolvimento Mobile**

## 🛠️ Tecnologias Utilizadas

- **[Flutter](https://flutter.dev)** - Framework para desenvolvimento multiplataforma
- **[Dart](https://dart.dev)** - Linguagem de programação
- **[BLoC](https://bloclibrary.dev)** - Gerenciamento de estado
- **[flutter_test](https://api.flutter.dev/flutter/flutter_test/flutter_test-library.html)** - Framework de testes
- **[integration_test](https://docs.flutter.dev/testing/integration-tests)** - Testes de integração

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter os seguintes requisitos instalados:

- Flutter SDK (versão 3.0.5 ou superior)
- Dart SDK (versão 3.0.5 ou superior)
- Android Studio / Xcode (para emuladores)
- VS Code ou Android Studio (recomendado com plugins Flutter e Dart)
- Git

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/OYanEnrique/flutter-ci-alura.git
cd flutter-ci-alura
```

### 2. Instale as dependências

```bash
flutter pub get
```

### 3. Execute o aplicativo

```bash
flutter run
```

### 4. Execute os testes

**Testes unitários:**
```bash
flutter test
```

**Testes de integração:**
```bash
flutter test integration_test/app_test.dart
```

## 📂 Estrutura do Projeto

```
lib/
├── layout/           # Cores, estilos e temas
├── logic/            # Lógica de negócio (Cubits)
│   ├── name_draw/
│   └── names_to_draw/
├── pages/            # Páginas do aplicativo
│   ├── home_page.dart
│   └── draw_page.dart
├── widgets/          # Componentes reutilizáveis
└── main.dart         # Ponto de entrada

test/
├── logic/            # Testes unitários da lógica
└── widgets/          # Testes de widgets

integration_test/     # Testes de integração
```

## 🧪 Testes

O projeto possui cobertura de testes em diferentes níveis:

- **Testes Unitários**: Validam a lógica de negócio isoladamente
- **Testes de Widget**: Verificam o comportamento dos componentes visuais
- **Testes de Integração**: Testam o fluxo completo da aplicação

## 🎓 Sobre o BootCamp

Este projeto foi desenvolvido como parte do **BootCamp Santander de Desenvolvimento Mobile 2025**, uma parceria entre Santander e Alura focada em capacitar desenvolvedores nas mais modernas tecnologias de desenvolvimento mobile.

## 📚 Recursos de Aprendizado

- [Documentação Flutter](https://docs.flutter.dev)
- [Curso Flutter CI - Alura](https://www.alura.com.br/)
- [BLoC Pattern](https://bloclibrary.dev)
- [Flutter Testing](https://docs.flutter.dev/testing)

## 👨‍💻 Autor

Desenvolvido durante o BootCamp Santander 2025 - Alura

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!

**#Flutter #Dart #CI #CD #Testing #Mobile #Alura #Santander**
