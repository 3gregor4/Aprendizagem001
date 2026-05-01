# Como rodar testes neste projeto

Este projeto utiliza **Vitest** e **Testing Library** para testes unitários e de integração.

## Comandos disponíveis

- `npm test`: Executa todos os testes em modo watch (padrão).
- `npm run test:ui`: Executa os testes com uma interface gráfica para visualização.

## Estrutura de arquivos
- Arquivos de teste devem ser nomeados com sufixo `.test.ts` ou `.test.tsx` (ex: `MyComponent.test.tsx`).
- O arquivo de configuração principal é o `vitest.config.ts`.
- O arquivo de setup dos testes é o `vitest.setup.ts`.
