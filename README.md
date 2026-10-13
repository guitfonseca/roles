# Onde a gente vai?

Lista pessoal de bares e rolês, publicada no GitHub Pages.

## Como adicionar lugares

1. Manda os prints (posts do Instagram, Maps etc.) pro Claude junto com o prompt abaixo.
2. Copia o JSON que ele devolver e cola dentro do array em `lugares.json`.
3. Commit. O Pages atualiza em ~1 minuto.

### Prompt

```
Extraia cada lugar destes prints como objetos JSON (só o array, sem texto).
Campos: id (slug), nome, tipo (bar|restaurante|cafe|balada|cultura|ar_livre|doce),
ocasioes (date|amigos|visita|sozinho|familia|trabalho — escolha as que fazem sentido
pelo clima do lugar), bairro, cidade, estado (UF), endereco, horarios, preco ($ a $$$$),
instagram (@), tags (3–5 palavras curtas), notas (dica útil se houver),
status: "quero-ir", adicionado: data de hoje.
Se um campo não aparece no print, omita — não invente horário nem endereço.
```

## Marcar como "já fui"

Troca `"status": "quero-ir"` por `"status": "ja-fui"`. O lugar sai da lista padrão e aparece riscado no filtro "Já fui".
