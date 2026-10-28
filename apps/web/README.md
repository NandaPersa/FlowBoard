# FlowBoard frontend
O front-end do FlowBoard será desenvolvido com angular usando a estrutura

``` 
src/app/core/{auth,http,config,guards}/
src/app/features/{workspace,projects,tasks,ai-context,insights,integrations}/
src/app/shared/{ui,pipes,utilities}/
```
- Standalone components, roteamento lazy-loaded por feature e Reactive Forms com validações espelhadas no servidor.
- Signals para estado local/view-model; RxJS para fluxos assíncronos, HTTP e composição de eventos; não introduzir NgRx no MVP sem necessidade comprovada.
- HttpInterceptor para erros comuns, sessão e correlation/request IDs quando aplicável; guards melhoram UX, mas jamais substituem autorização da API.
- Angular Material como base de acessibilidade visual; estados de carregamento, erro, vazio e ausência de métricas explicitamente projetados.


## Tecnologias

- Angular 22;
- TypeScript 6.0;
- Angular Material
- Node.js 24 LTS
