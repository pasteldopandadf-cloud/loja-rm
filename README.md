# Loja RM

Planejador da loja em realidade mista para o Meta Quest 3, que também roda no navegador do computador.

- **Abrir:** https://pasteldopandadf-cloud.github.io/loja-rm/
- **No Quest 3:** abra o link no navegador do Quest e toque em *Entrar em realidade mista*. Permita o acesso ao espaço para que paredes, piso e móveis reais virem colisão. Se nada for detectado, faça a configuração do espaço em Configurações > Espaço físico.
- **Controles no Quest:** o menu fica no controle esquerdo. Gatilho pega e solta, grip aciona motores, analógico gira e aproxima.
- **Controles no computador:** clique seleciona, W move, E gira, F aciona, Shift+clique empurra, Del apaga, espaço pausa a física.

- **Modelos 3D reais:** escaneie no iPhone (Scaniverse ou Polycam), exporte em GLB e use *Importar modelo .glb*. O modelo fica guardado no navegador e pode ser fixo ou solto (com física).
- **Scan da sala:** ao sair da realidade mista no Quest, as superfícies escaneadas ficam salvas e podem ser baixadas como `scan-da-sala.glb`.

Feito com Three.js 0.160 e cannon-es 0.20, num único `index.html`.
