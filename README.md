# Essential Spring Boot Snippets

This extension is optimized for developers who wants to develop Java Spring Boot applications.  These code snippets contains **Java** and **EditorConfig** snippets.

This extension is still in progress. [Let me know](https://github.com/doggy8088/spring-boot-snippets/issues) if you have any suggestion! Thanks!

## Features

- Provide `Java`, `Controller`, `EditorConfig` and `VSCode User Settings` snippets
- Provide `DTO` snippets with [Lombok](https://projectlombok.org/) & [spring-boot-starter-validation](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation) dependency
- Bundled with some must needed VSCode extensions

## Code Snippets

### Spring Boot (`.java`)

| Prefix           | Description                                         |
| ---------------- | --------------------------------------------------- |
| `api-controller` | Generate RestController                             |
| `api-get`        | Spring Boot Controller GET action                   |
| `api-get-all`    | Spring Boot Controller GET action for all items     |
| `api-get-by-id`  | Spring Boot Controller GET action for one item      |
| `api-get-query`  | Spring Boot Controller GET action with RequestParam |
| `api-post`       | Spring Boot Controller POST action                  |
| `api-put`        | Spring Boot Controller PUT action                   |
| `api-delete`     | Spring Boot Controller DELETE action                |
| `api-dto`        | Generate DTO class for an API action                |

> The `api-dto` snippet need `lombok` and `spring-boot-starter-validation` dependencies been installed in the project.

### Java (`.java`)

| Prefix          | Description                   |
| --------------- | ----------------------------- |
| `sout`          | Print a string to System.out  |
| `serr`          | Prints a string to System.err |
| `private_field` | Private field                 |
| `public_field`  | Public field                  |
| `st`            | String                        |
| `thr`           | throw new                     |

### EditorConfig (`.editorconfig`)

| Prefix | Description                                |
| ------ | ------------------------------------------ |
| `java` | Generates `.editorconfig` for Java project |

### VSCode User Settings (`.json`)

| Prefix | Description                                      |
| ------ | ------------------------------------------------ |
| `java` | Generates VSCode User Settings for Java projects |

## Extensions

This extension bundled with some MUST needed VSCode extensions for Java Spring Boot developments.

- [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

  - [Language Support for Java™ by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
    - Code Navigation
    - Auto Completion
    - Refactoring
    - Code Snippets
  - [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
    - Debugging
  - [Java Test Runner](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)
    - Run & Debug JUnit/TestNG Test Cases
  - [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
    - Project Scaffolding
    - Custom Goals
  - [Project Manager for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-dependency)
    - Manage Java projects, referenced libraries, resource files, packages, classes, and class members
  - [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
    - AI-assisted development
    - Completion list ranked by AI

- [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack)

  - [Spring Initializr Java Support](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-initializr)

      Quickly generate a Spring Boot project in Visual Studio Code (VS Code). It helps you to customize your projects with configurations and manage Spring Boot dependencies.

  - [Spring Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard)

      With an explorer in the side bar, you can view and manage all available Spring Boot projects in your workspace. It also supports the features to quickly start, stop or debug a Spring Boot project.

  - [Spring Boot Tools](https://marketplace.visualstudio.com/items?itemName=pivotal.vscode-spring-boot)

      Provides validation and content assist for Spring Boot `application.properties`, `application.yml` properties files. As well as Boot-specific support for `.java` files.

- [Java Decompiler](https://marketplace.visualstudio.com/items?itemName=dgileadi.java-decompiler)

    This extension allows you to decompile Java class files.

- [Lombok Annotations Support for VS Code](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-lombok)

    A lightweight extension to support [Lombok](https://projectlombok.org/) annotations processing in Visual Studio Code

- [Dependency Analytics](https://marketplace.visualstudio.com/items?itemName=redhat.fabric8-analytics)

    Dependency Analytics is powered by [Snyk Intel Vulnerability DB](https://snyk.io/product/vulnerability-database/), it is the most advanced and accurate open source vulnerability database in the industry. That adds value with the latest, fastest and more number of vulnerabilities derived from numerous sources.

- [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)

    Viewing `target/site` or [JaCoCo](https://www.jacoco.org/) report can use this extension very easily.

- [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

    XML Language Support by Red Hat.

- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

    YAML Language Support by Red Hat, with built-in Kubernetes syntax support.

    Spring support two types of configuration: `application.properties` and `application.yml`

- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

    REST Client for Visual Studio Code. Really useful tool. You should definitely try it.

- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

    EditorConfig Support for Visual Studio Code

I also recommend the following extensions you MIGHT need.

- Linting

  - [Checkstyle for Java](https://marketplace.visualstudio.com/items?itemName=shengchen.vscode-checkstyle)

      Provide real-time feedback about Checkstyle violations and quick fix actions

  - [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)

      SonarLint helps you detect and fix quality issues as you write code in Java.

- Tomcat and Jetty

  - [Tomcat for Java](https://marketplace.visualstudio.com/items?itemName=adashen.vscode-tomcat)

      Debug or run your java war package in Apache Tomcat.

  - [Jetty for Java](https://marketplace.visualstudio.com/items?itemName=SummerSun.vscode-jetty)

      Start and run or debug your war package on Jetty.

- Java Tools

  - [Gradle Language Support](https://marketplace.visualstudio.com/items?itemName=naco-siren.gradle-language)

      Add Gradle language support for Visual Studio Code

  - [Gradle Tasks](https://marketplace.visualstudio.com/items?itemName=richardwillis.vscode-gradle)

      Run Gradle tasks in VS Code

  - [Quarkus](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-quarkus)

      [Quarkus Tools for Visual Studio Code](https://quarkus.io/) is a feature-packed extension tailored for Quarkus application development within Visual Studio Code. You can quickly get started by using the extension's project generation and project debugging feature. The extension also provides amazing language features (completion, hover, validation etc.) for your project's `application.properties` file.

- Containers and Microservices

  - [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)

      Build docker images and work with image registries.

  - [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)

      It provides an explorer view to manage clusters and the nodes inside. It also provides advanced syntax support for editing Kubernetes manifest files.

- Workbench

  - [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

      Show `TODO`, `FIXME`, etc. comment tags in a tree view

  - [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)

      Syntax highlighting for log files

  - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

      Material Design Icons for Visual Studio Code

- Containerization

  - [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

      Makes it easy to create, manage, and debug containerized applications.

  - [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)

      Develop, deploy and debug Kubernetes applications.

- Git Version Control

  - [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=doggy8088.git-extension-pack)

      Popular Visual Studio Code extensions for Git version control including [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens), [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) and [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph).

## Recommended VSCode User Settings

- `settings.json`

    ```json
    {
        "java.debug.settings.hotCodeReplace": "auto",
        "java.saveActions.organizeImports": true,
        "editor.foldingImportsByDefault": true
    }
    ```

- `.vscode/launch.json`

    ```json
    {
        "configurations": [
            {
                "type": "java",
                "request": "launch",
                "name": "Launch Spring Boot",
                "mainClass": "${workspaceFolder}/src/main/java/com/example/demo1/Demo1Application.java",
                "envFile": "${workspaceFolder}/.env"
            }
        ]
    }
    ```

    > Remember change `mainClass` to your class that contains **main()** method.

## Contributing

If you need any Java / Spring Boot snippets, please feel free to send PRs to me or simply [drop me a note](https://github.com/doggy8088/spring-boot-snippets/issues)! 😊

---

**Enjoy!**
