# Essential Spring Boot Snippets

This extension is optimized for developers who wants to develop Java Spring Boot applications.  These code snippets contains **Java** and **EditorConfig** snippets.

This extension is still in progress.  [Let me know](https://github.com/doggy8088/spring-boot-snippets/issues) if you have any suggestion! Thanks!

## Features

- Provide Controller, EditorConfig and VSCode User Settings snippets
- Provide DTO snippets with [Lombok](https://projectlombok.org/) & [spring-boot-starter-validation](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation) dependency
- Bundled with some must needed VSCode extensions

## Code Snippets

### Java (`.java`)

| Prefix           | Description                                         |
| ---------------- | --------------------------------------------------- |
| `api-controller` | Generate RestController                             |
| `api-get-all`    | Spring Boot Controller GET action for all items     |
| `api-get-by-id`  | Spring Boot Controller GET action for one item      |
| `api-get-query`  | Spring Boot Controller GET action with RequestParam |
| `api-post`       | Spring Boot Controller POST action                  |
| `api-put`        | Spring Boot Controller PUT action                   |
| `api-delete`     | Spring Boot Controller DELETE action                |
| `api-dto`        | Generate DTO class for an API action                |

### EditorConfig (`.editorconfig`)

| Prefix | Description                                |
| ------ | ------------------------------------------ |
| `java` | Generates `.editorconfig` for Java project |

### VSCode User Settings (`.json`)

| Prefix        | Description                                                    |
| ------------- | -------------------------------------------------------------- |
| `java`        | Generates VSCode User Settings for Java & Spring Boot projects |
| `spring-boot` | Generates VSCode User Settings for Java & Spring Boot projects |

## Extensions

This extension bundled with some MUST needed VSCode extensions for Java Spring Boot developments.

- [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
  - [Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
  - [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
  - [Java Test Runner](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)
  - [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
  - [Project Manager for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-dependency)
  - [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

- [Java Decompiler](https://marketplace.visualstudio.com/items?itemName=dgileadi.java-decompiler)

    This extension allows you to decompile Java class files.

- [Spring Initializr Java Support](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-initializr)

    Quickly generate a Spring Boot project in Visual Studio Code (VS Code). It helps you to customize your projects with configurations and manage Spring Boot dependencies.

- [Spring Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard)

    With an explorer in the side bar, you can view and manage all available Spring Boot projects in your workspace. It also supports the features to quickly start, stop or debug a Spring Boot project.

- [Spring Boot Tools](https://marketplace.visualstudio.com/items?itemName=pivotal.vscode-spring-boot)

    Provides validation and content assist for Spring Boot `application.properties`, `application.yml` properties files. As well as Boot-specific support for `.java` files.

- [Lombok Annotations Support for VS Code](https://marketplace.visualstudio.com/items?itemName=GabrielBB.vscode-lombok)

    A lightweight extension to support [Lombok](https://projectlombok.org/) annotations processing in Visual Studio Code

- [Dependency Analytics](https://marketplace.visualstudio.com/items?itemName=redhat.fabric8-analytics)

    Dependency Analytics is powered by [Snyk Intel Vulnerability DB](https://snyk.io/product/vulnerability-database/), it is the most advanced and accurate open source vulnerability database in the industry. That adds value with the latest, fastest and more number of vulnerabilities derived from numerous sources.

- [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)

    Viewing `target/site` or [JaCoCo](https://www.jacoco.org/) report can use this extension very easily.

- [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

I also recommend the following extensions you MIGHT need.

- Code Quality

  - [Checkstyle for Java](https://marketplace.visualstudio.com/items?itemName=shengchen.vscode-checkstyle)

      Provide real-time feedback about Checkstyle violations and quick fix actions

  - [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)

      SonarLint helps you detect and fix quality issues as you write code in Java.

- Java Tools

  - [Tomcat for Java](https://marketplace.visualstudio.com/items?itemName=adashen.vscode-tomcat)

      Debug or run your java war package in Apache Tomcat.

  - [Gradle Language Support](https://marketplace.visualstudio.com/items?itemName=naco-siren.gradle-language)

      Add Gradle language support for Visual Studio Code

  - [Gradle Tasks](https://marketplace.visualstudio.com/items?itemName=richardwillis.vscode-gradle)

      Run Gradle tasks in VS Code

- Workbench

  - [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

      Show TODO, FIXME, etc. comment tags in a tree view

  - [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)

      Syntax highlighting for log files

  - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

      Material Design Icons for Visual Studio Code

- Testing

  - [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

      REST Client for Visual Studio Code

- Containerization

  - [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

      Makes it easy to create, manage, and debug containerized applications.

- Git Version Control

  - [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)

      View a Git Graph of your repository, and perform Git actions from the graph.

  - [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)

      Language support for `.gitignore` files.

  - [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

      Supercharge the Git capabilities built into Visual Studio Code

## Recommended VSCode User Settings

- `settings.json`

    ```json
    {
        "java.home": "/usr/lib/jvm/java-11-openjdk-amd64",
        "java.debug.settings.hotCodeReplace": "auto",
        "java.configuration.runtimes": [
            {
                "name": "JavaSE-1.8",
                "path": "/usr/lib/jvm/java-8-openjdk-amd64/",
                "sources": "/usr/lib/jvm/java-8-openjdk-amd64/src.zip",
                "default": true
            },
            {
                "name": "JavaSE-11",
                "path": "/usr/lib/jvm/java-11-openjdk-amd64",
                "sources": "/usr/lib/jvm/java-11-openjdk-amd64/lib/src.zip",
                "javadoc": "https://docs.oracle.com/en/java/javase/11/docs/api"
            }
        ],
        "spring-boot.ls.java.home": "/usr/lib/jvm/java-11-openjdk-amd64",
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

    > [Issue #140: How to read .env file when start spring boot app?](https://github.com/microsoft/vscode-spring-boot-dashboard/issues/140)

## Contributing

If you need any Java / Spring Boot snippets, please feel free to send PRs to me or simply [drop me a note](https://github.com/doggy8088/spring-boot-snippets/issues)! 😊

---

**Enjoy!**
