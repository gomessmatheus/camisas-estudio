# 👕 Camisas — Estúdio

Sistema de controle de camisas do estúdio. Permite visualizar onde cada camisa está, quem é o dono e fazer reservas por data.

## Funcionalidades

- Cadastro de camisas com foto, time, liga, número e temporada
- Controle de localização: Casa · Estúdio · Lavanderia · Empréstimo
- Cadastro de pessoas (donos) com cor identificadora
- Filtro rápido por dono, local e liga
- Agrupamento por time
- Reserva de camisa por nome e data
- Dados salvos no navegador (localStorage)

## Estrutura do projeto

```
camisas-estudio/
├── index.html       # App completo (HTML + CSS + JS em um único arquivo)
├── netlify.toml     # Configuração de deploy no Netlify
└── README.md        # Este arquivo
```

## Como rodar localmente

Basta abrir o `index.html` diretamente no navegador. Não precisa de servidor ou dependências.

## Deploy

O projeto está configurado para deploy automático via Netlify.  
Qualquer push na branch `main` publica uma nova versão automaticamente.

## Dados e armazenamento

Os dados ficam salvos no `localStorage` do navegador de quem cadastrou.  
Para um sistema colaborativo com todos editando em tempo real, o próximo passo seria integrar com [Supabase](https://supabase.com).

## Próximos passos sugeridos

- [ ] Migrar dados para banco na nuvem (Supabase) para acesso compartilhado
- [ ] Adicionar histórico de movimentações por camisa
- [ ] Notificação quando uma camisa reservada está disponível
- [ ] Exportar lista em PDF ou planilha
