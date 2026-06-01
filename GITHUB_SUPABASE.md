# Configuracao GitHub Pages + Supabase

1. No Supabase, execute `supabase.sql` no SQL Editor.
2. No GitHub, cadastre os secrets:

```text

NEXT_PUBLIC_SUPABASE_URL = 'https://dubollsfzwboosuekjwm.supabase.co/rest/v1/';
NEXT_PUBLIC_SUPABASE_ANON_KEY = 'sb_publishable_ZKh_wu4scmNemRz4VKHCyQ_WluJmg7b';
```

3. Em `Settings > Pages`, selecione `GitHub Actions`.
4. Rode o workflow `Publicar GitHub Pages`.

Se o login mostrar `Nao foi possivel acessar o Supabase`, abra a pagina publicada e confirme no DevTools > Network se a chamada para `https://fcijhxqdfpykdsnbkatw.supabase.co` esta liberada. Se o projeto estiver pausado ou os secrets estiverem antigos, o navegador retornara `Failed to fetch`.

Login inicial:

```text
admin@semed.local
adm123
```
