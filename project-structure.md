mcpTools/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── mcptools/
│   │           ├── core/
│   │           │   ├── AbstractMCPTool.java
│   │           │   ├── MCPTool.java
│   │           │   ├── MCPToolRegistry.java
│   │           │   ├── MCPParameter.java
│   │           │   └── ToolRegistry.java
│   │           │
│   │           ├── tools/
│   │           │   ├── KVGetTool.java
│   │           │   └── ... (other specific tool implementations)
│   │           │
│   │           └── runners/
│   │               ├── ToolRunner.java
│   │               └── ToolRunnerOOP.java
│   │
│   └── test/
│       └── java/
│           └── mcptools/
│               └── ... (unit tests)
│
├── lib/
│   └── src/
│       └── main/
│           └── java/
│               └── (existing library code)
│
├── gradle/
├── docs/
│   └── cct-mojo-prompt.md
│
├── build.gradle.kts
├── settings.gradle.kts
├── gradlew
├── gradlew.bat
└── README.md
