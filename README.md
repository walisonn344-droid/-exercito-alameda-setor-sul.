# Exército de Alameda — Setor Sul

Pacote inicial organizado para GitHub, preservando o painel HTML recebido.

## Conteúdo
- `frontend/index.html`: protótipo visual original. Nesta versão os dados são guardados no navegador (localStorage); ainda não sincroniza entre aparelhos.
- `backend/`: estrutura inicial Spring Boot.
- `supabase/`: arquivo SQL inicial de referência; não execute em produção sem revisar as políticas RLS.

## Importante antes de publicar
Este pacote **não é ainda um sistema multiusuário de produção**. O HTML original usa armazenamento local e contém regras antigas de aprovação/cadastro. Não use dados reais nem publique como sistema seguro antes de integrar autenticação e banco de dados.

## Próximas configurações
1. Criar um repositório no GitHub e enviar o conteúdo desta pasta.
2. Configurar o projeto Supabase (URL e chave pública/anon no frontend; nunca colocar `service_role` no navegador).
3. Implementar autenticação Supabase, tabelas e políticas RLS para separar os dados de cada conta.
4. Configurar o administrador inicial `SR Machado` por um processo seguro de criação de usuário; nenhuma senha foi definida ou incluída neste pacote.
5. Implementar e testar o fechamento semanal configurável (padrão terça-feira, 15h30), arquivando o ranking antes de zerar o atual.

## Execução local do protótipo
Abra `frontend/index.html` no navegador. Isso demonstra a interface, mas não fornece autenticação segura nem sincronização online.

