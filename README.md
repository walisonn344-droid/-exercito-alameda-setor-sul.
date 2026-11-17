# Exército de Alameda
Repositório inicial do aplicativo privado do Exército de Alameda.

## Estrutura
- `app/`: aplicativo Flutter para Android e iOS.
- `supabase/schema.sql`: estrutura inicial PostgreSQL/Supabase.

## Começar
1. Instale o Flutter.
2. Entre na pasta `app` e execute `flutter pub get`.
3. Crie um projeto Supabase.
4. Revise e execute `supabase/schema.sql` no SQL Editor.
5. Configure a conexão do aplicativo com o Supabase usando somente credenciais públicas apropriadas.
6. Nunca envie senhas, arquivos `.env` ou a chave `service_role` para o GitHub.

Este é um ponto de partida, não uma versão pronta para produção. Autenticação, aprovação, permissões e políticas RLS precisam ser implementadas e testadas antes de cadastrar integrantes reais.
