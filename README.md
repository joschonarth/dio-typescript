<p align="center">
  <img src="assets/typescript.png">
</p>

# <img src="https://skillicons.dev/icons?i=typescript&theme=dark" width="35" align="center"> Introdução Prática ao TypeScript

Este repositório tem como objetivo apresentar uma introdução prática ao **TypeScript**, abordando seus principais conceitos e exemplos práticos para ajudar no aprendizado da linguagem.

## 🚀 Instalação

Antes de instalar o TypScript propriamente você precisa ter o Pacote de Gerenciamento do Node instalado.

### <img src="https://skillicons.dev/icons?i=nodejs&theme=dark" width="25" align="center"> Instalação do Node.js

1. Instale o Node.js:
- Acesse o site oficial do [Node.js](https://nodejs.org) e baixe a versão mais recente.
- Siga as instruções de instalação fornecidas para o seu sistema operacional.

**2. Verifique a instalação:**
```bash
node -v
npm -v
```
Os comandos acima devem retornar as versões instaladas do Node.js e do npm, respectivamente.

### <img src="https://skillicons.dev/icons?i=typescript&theme=dark" width="25" align="center"> Instalação do TypeScript

**1. Instalar TypeScript globalmente:**

```bash
npm install -g typescript
```

Ou você pode optar por instalar o TypeScript como dependência de desenvolvimento:

```bash
npm install typescript -D
```

**2. Inicializar um projeto Node.js:**

```bash
npm init -y
```

## ⚙️ Configuração

**1. Criar o arquivo de configuração do TypeScript (`tsconfig.json`):**

```bash
npx tsc --init
```

**2. Instalar o TS Node Dev para desenvolvimento:**

```bash
npm install ts-node-dev
```

## 🚀 Como Rodar

**1. Compilar um arquivo TypeScript para JavaScript:**

```bash
npx tsc arquivo.ts
```

**2. Executar o arquivo JavaScript gerado:**

```bash
node arquivo.js
```

**3. Rodar o script com TS Node Dev:**

```bash
ts-node-dev arquivo.ts
```

## 🛠️ Configuração do PowerShell (caso necessário)

**1. Permitir scripts locais no PowerShell:**

```bash
set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

**2. Verificar as políticas de execução:**

```bash
Get-ExecutionPolicy -List
```

## 📃 Recursos Adicionais

- [Documentação oficial do TypeScript](https://www.typescriptlang.org/docs/)
- [Guia prático para TypeScript](https://www.typescriptlang.org/)