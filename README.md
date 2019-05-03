# Counter-Strike Global Offensive, arquivos de configuração

A.K.A.: CSGO cfg.

## O que tem nela?

- Configurações pessoais (`hero.cfg`).
  - Para jogar normalmente.
- Configurações para servidores.
  - Inclusive servidores privados `treino_bots.cfg` e `nadetraining`. [Link "oficial" do nadetraining](https://github.com/s-ol/csgo-vscripts).
  - O restante é para servidores dedicados com Warmode e DM ffa instalados.
- As variáveis na cfg pessoal está organizada por tópico e comentada (não tem perdido :D).
- Várias binds úteis, como as de compras e spam.
- O script de treino de granadas em que salva o último local das granadas, bastante útil para treinar flashbangs.

## Como usar?

- É bem simples, basta baixar a CFG e editar com o bloco de notas (ou seu editor de texto favorito) para ajustar com suas preferências (como é o caso da sensibilidade).
- Depois coloque na pasta de cfg do cs: `local_que_a_pasta_da_steam_esta\steamapps\common\Counter-Strike Global Offensive\csgo\cfg\`.  
- Execute a cfg com o comando de inicialização `+exec nomeDaCfg` ou abra o console e digite `exec nomeDaCfg`.  
- Coloque o conteúdo da pasta `vscripts` dentro de `local_que_a_pasta_da_steam_esta\steamapps\common\Counter-Strike Global Offensive\csgo\scripts\vscripts\` e a cfg `nadetraining.cfg` dentro da pasta de cfg do cs. Execute a cfg `nadetraining` dentro do seu mapa de treino, recomendo usar também a cfg `treino_bots`.