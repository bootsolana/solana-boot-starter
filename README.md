# Solana Boot Starter

A **Spring Boot Starter** to interact with the Solana blockchain. Designed to simplify blockchain development for Java/Kotlin developers. 
Making it easy to integrate Solana functionalities into your Spring Boot projects, reducing boilerplate and accelerating development.

## Features

- 🛠 **Easy integration**: Simplify the process of interacting with Solana RPC nodes.
- 📡 **RPC Client Support**: Utilize Solana's JSON-RPC endpoints through Solanaj.
- 🔑 **Transaction Support**: Perform transfers, interact with accounts, and execute on-chain transactions.
- 🚀 **Spring Boot Auto-Configuration**: Automatically configure Solana bean to interact with the blockchain.

## Solanaj
- https://github.com/skynetcap/solanaj

## Getting Started

### Prerequisites
- A Solana RPC endpoint (e.g., https://api.mainnet-beta.solana.com or a devnet endpoint).

### Installation
Add the starter to your Spring Boot project's dependencies:

#### Gradle (Kotlin DSL)
```kotlin
dependencies {
    implementation("io.bootsolana:solana-boot-starter:1.0.0")
}
```

#### Maven
```xml
<dependency>
    <groupId>io.bootsolana</groupId>
    <artifactId>solana-boot-starter</artifactId>
    <version>1.0.0</version>
</dependency>

```

## Properties Configuration
#### Add the following properties to your application.yml or application.properties
```yml
solana:
  enabled: true
  endpoint: "https://api.devnet.solana.com" # Replace with your preferred RPC endpoint
```



