- 安装deno:https://deno.land/
- [使用 Import maps] (https://deno.land/manual/linking_to_external_code/import_maps)
- 使用 Import maps 的启动命令：
```sh
deno run --allow-net  --importmap=import_map.json --unstable  Server.tsx
```
- 启动命令：
```sh
deno run --allow-net Server.tsx
```