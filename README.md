# Rise Tracker — Community Edition

Ferramenta comunitária e não oficial para acompanhar as falas da Rise em **Persona 4 Golden (PC/Steam)** e ajudar na conquista **Hardcore Risette Fan**.

## Como usar

1. Abra o site publicado pelo GitHub Pages.
2. Selecione uma **cópia** do arquivo `data000X.bin` no campo **Save atual**.
3. Filtre por personagem, situação, falas registradas ou faltantes.
4. Opcionalmente, importe outro save mais antigo da mesma campanha para ver novos registros.

**Onde ficam os saves no Windows (Steam):** `Steam\userdata\SEU_ID\1113000\remote\data0001.bin` (o número varia por slot).

O site lê os saves **apenas no navegador**, sem enviá-los para a internet e sem escrever neles. Não é necessário instalar Cheat Engine.

## Compatibilidade e limites

- Validado com arquivos `.bin` de **217.937 bytes** da versão PC/Steam; consoles e outros formatos não foram validados.
- O mapa de **625 flags** está incluído no HTML.
- Os textos originais são carregados de uma lista pública de `rise.tsv` no repositório [p4g-ct](https://github.com/zarroboogs/p4g-ct) (ou importados manualmente). Sem conexão, as IDs e orientações permanecem disponíveis.
- Algumas condições e falas de chefes são estimativas e podem não contar para a conquista. Use as etiquetas de confiabilidade.
- O site não salva uploads nem os envia a servidores. O carregamento dos textos consulta uma fonte pública no GitHub.

## Publicação no GitHub Pages

Este repositório contém o site completo em `index.html`, na branch `main`.
Para ativar a hospedagem pela primeira vez:

1. Abra **Settings → Pages** no repositório.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha `main` e `/(root)`, depois **Save**.
4. Quando a publicação terminar, acesse [Rise Tracker](https://shinkiz0805.github.io/Rise-Tracker/).

Os arquivos `data000X.bin` dos jogadores são processados no navegador, não são incluídos neste repositório.

## Créditos e fontes

- Mapeamento das flags: [zarroboogs/p4g-ct](https://github.com/zarroboogs/p4g-ct).
- Orientações para a conquista: [Guia Hardcore Risette Fan no GameFAQs](https://gamefaqs.gamespot.com/xbox-series-x/370653-persona-4-golden/faqs/81937/hardcore-risette-fan).

Projeto de fã não oficial, sem vínculo com Atlus, SEGA ou os autores dos materiais de referência.