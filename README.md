# Essential Spring Boot Snippets

This extension is optimized for developers who wants to develop Java Spring Boot applications.  These code snippets contains **Java** and **EditorConfig** snippets.

This extension is still in progress.  [Let me know](https://github.com/doggy8088/spring-boot-snippets/issues) if you have any suggestion! Thanks!

## Features

- Provide Controller snippets
- Provide DTO snippets with Lombok annotations
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

## Extensions

This extension bundled with some MUST needed VSCode extensions for Java Spring Boot developments.

- [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
  - [Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
  - [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
  - [Java Test Runner](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)
  - [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
  - [Project Manager for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-dependency)
  - [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [Spring Initializr Java Support](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-initializr)
- [Spring Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard)
- [Spring Boot Tools](https://marketplace.visualstudio.com/items?itemName=pivotal.vscode-spring-boot)
- [Lombok Annotations Support for VS Code](https://marketplace.visualstudio.com/items?itemName=GabrielBB.vscode-lombok)
- [Dependency Analytics](https://marketplace.visualstudio.com/items?itemName=redhat.fabric8-analytics)
- [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

I also recommend the following extensions you MIGHT need.

- [Checkstyle for Java](https://marketplace.visualstudio.com/items?itemName=shengchen.vscode-checkstyle)

    Provide real-time feedback about Checkstyle violations and quick fix actions

- [Tomcat for Java](https://marketplace.visualstudio.com/items?itemName=adashen.vscode-tomcat)

    Debug or run your java war package in Apache Tomcat.

- [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)

    SonarLint helps you detect and fix quality issues as you write code in Java.

- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

    Show TODO, FIXME, etc. comment tags in a tree view

- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

    REST Client for Visual Studio Code

- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)

    View git log, file history, compare branches or commits

- [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)

    Language support for `.gitignore` files.

- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

    Supercharge the Git capabilities built into Visual Studio Code

## Recommended VSCode User Settings

- `settings.json`

    ```json
    {
        "java.home": "/usr/lib/jvm/java-11-openjdk-amd64",
        "spring-boot.ls.java.home": "/usr/lib/jvm/java-11-openjdk-amd64",
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
        ]
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
