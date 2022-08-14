# added required pakcages
yarn add fastify env-schema fastify-swagger nanoid@3.3.4 @fastify/type-provider-json-schema-to-ts @typegoose/typegoose mongoose @sinclair/typebox

yarn add @types/node typescript @commitlint/config-conventional @commitlint/cli @commitlint/{cli,config-conventional} husky prettier vitest tsx -D

# create ts config file
npx tsc --init

# add the script section to package.json 
```json
"scripts":{
  "build":"tsc",
  "dev": "tsx watch src/app.ts",
  "test": "vitest"
}
```