# Intro-to-Typescript

Steps to setup and run the Typscript project.

## Installation of required Libraries

+ First, install TypeScript Globally using this command

```console
npm install -g typescript
```

+ Secondly, install ts-node library to enable execute the typescript file directly. `ts-node` is a TypeScript execution engine and REPL for Node.js. It JIT transforms TypeScript into JavaScript, enabling you to directly execute TypeScript on Node.js without precompiling.

```console
npm install -g ts-node
```

+ Next, install all dependencies of the project.
  
```console
npm install
```

## How to run

To run typscript:

```console
npm run start
```

OR

```console
ts-node <fileName.ts>
```

VS code extension `Code Runner` also works which also runs the second command internally.

## How to get Transpiled Files

To transpile from .ts files to .js files:

```console
npm run build
```

Internally it clean build files using `rimraf <foldername>` and runs the command `tsc` execute transpilation of all .ts files to .js files.
