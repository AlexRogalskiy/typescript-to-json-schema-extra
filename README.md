# typescript-to-json-schema-extra

Provides some extras for [typescript-to-json-schema](https://github.com/xiag-ag/typescript-to-json-schema).

- Generate schemas for all types: `SchemaGenerator.createSchemas(filter: (fileName: string) => boolean): Map<Schema>`.
- Create a program from a list of files: `ExtConfig.paths`.
- Provide custom compiler options for a program: `createProgram(config: Config, options?: ts.CompilerOptions): ts.Program`.
- Treat line comments `//` the same as jsDoc comments `/** */`: `ExtConfig.lineComment`.

