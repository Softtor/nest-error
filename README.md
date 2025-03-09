# nest-error


[Nest] 234516  - 09/03/2025, 19:40:52     LOG [NestFactory] Starting Nest application...
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] AppModule dependencies initialized +14ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] DatabaseModule dependencies initialized +0ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] PassportModule dependencies initialized +0ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] ConfigHostModule dependencies initialized +1ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] DiscoveryModule dependencies initialized +0ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] ConfigModule dependencies initialized +0ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] ConfigModule dependencies initialized +0ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] EventEmitterModule dependencies initialized +0ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] EnvConfigModule dependencies initialized +0ms
[Nest] 234516  - 09/03/2025, 19:40:52     LOG [InstanceLoader] JwtModule dependencies initialized +1ms
[Nest] 234516  - 09/03/2025, 19:40:52   ERROR [ExceptionHandler] TypeError: Cannot read properties of undefined (reading 'emit')
    at new AuthService (/home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/src/auth/auth.service.ts:33:23)
    at Injector.instantiateClass (/home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/node_modules/@nestjs/core/injector/injector.js:373:19)
    at callback (/home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/node_modules/@nestjs/core/injector/injector.js:65:45)
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async Injector.resolveConstructorParams (/home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/node_modules/@nestjs/core/injector/injector.js:145:24)
    at async Injector.loadInstance (/home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/node_modules/@nestjs/core/injector/injector.js:70:13)
    at async Injector.loadProvider (/home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/node_modules/@nestjs/core/injector/injector.js:98:9)
    at async /home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/node_modules/@nestjs/core/injector/instance-loader.js:56:13
    at async Promise.all (index 3)
    at async InstanceLoader.createInstancesOfProviders (/home/jvtuta/Documentos/code/estofaria-xingu/estofaria-xingu-backend/node_modules/@nestjs/core/injector/instance-loader.js:55:9)