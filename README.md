# Instituto Vértice · Portal Acadêmico

Protótipo acadêmico desenvolvido em React, TypeScript, React Router e Vite. Inclui login demonstrativo com verificação em duas etapas, cadastro, dashboard, notas, disciplinas, pré-matrícula, página institucional e perfil.

## Iniciar

```bash
npm install
npm run dev
```

Abra o endereço local exibido pelo Vite. Para gerar a versão de produção, rode `npm run build`.

## Demonstração

As credenciais e as limitações do modo demonstrativo estão documentadas em [DEMO.md](./DEMO.md). Os dados acadêmicos e as imagens do campus são ilustrativos; não representam uma instituição ou instalações reais.

O estado de login fica apenas em `sessionStorage`. O perfil e a seleção de pré-matrícula ficam no `localStorage` deste navegador. O formulário de cadastro não persiste CPF ou senha. A autenticação não substitui validação em servidor e não deve ser usada com dados reais.
