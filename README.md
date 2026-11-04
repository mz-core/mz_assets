# mz_assets

Resource compartilhado de imagens de itens para as interfaces MZ. Instale a pasta
`mz_assets` em `resources` e inicie-a antes do `mz_inventory`:

```cfg
ensure mz_assets
ensure mz_inventory
```

As imagens de `itens/` são declaradas no manifesto e acessadas pela NUI em
`https://cfx-nui-mz_assets/itens/<arquivo>`. Respeite maiúsculas e minúsculas
dos nomes em servidores Linux. O pacote do inventário depende deste resource;
os dois ZIPs são distribuídos separadamente.
