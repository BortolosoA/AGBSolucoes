
<br>
<p align="center">
  Esta é uma solução gratuita de Auto Instaladores, com o intuido de ajudar toda a comunidade a instalar as principais ferramentas do mercado de Automações/Marketing.
  <b>Você não precisa instalar todos, você poderá escolher qual das ferramentas você quer instalar.</b>
</p>

</p>
<br>
-->
## ✨ Ferramentas

Com essa solução, você consegue instalar as seguintes ferramentas:
- ⚡ <b>Chatwoot</b> -------> v3.2.0
- ⚡ <b>Evolution API</b> ---> 1.5.4
- ⚡ <b>Typebot</b> ---------> New: Escolha a versão
- ⚡ <b>N8N</b> -------------> New: Escolha a versão
- ⚡ <b>Appsmith</b> -------> Latest

## 📌 Observação

- Recomendamos que use a VPS da <b>Contabo</b> ou <b>Hetnerz</b> com o sistema <b>Ubuntu 20.04 LST 64x</b>! Foi realizado teste de instalação das ferramentas multiplas vezes usando uma VPS da Contabo com 8Gb Ram + 4vCores + Ubuntu 20.04 LST 64x.
- Caso for utilizar outra VPS, verifique se as portas escolhidas na instalação estão abertas.
- Se tiver qualquer ferramenta na sua VPS em produção, realize Snapshot da sua VPS antes, para evitar eventuais problemas.
- Os dados preenchidos no instalação não são enviados para nenhum lugar!
- Ao solicitar ajuda com outros membros, esconda sempre os dados sensiveis da sua instalação (keys, pass, tokens..)
- Você não precisa de solicitar autorização para usar esse instalador em cursos e/ou videos, apenas de os creditos.
## 💽 Instalação

Não são muitos passos para utilizar essa solução, mas é importante prestar atenção em cada detalhe para evitar ter dor de cabeça por eventuais problemas.

<p><b>1a-</b> Não tenho o <b>Setup</b> na minha VPS:</p>

```
sudo apt upgrade -y && sudo apt update && sudo apt install -y git && git clone https://github.com/BortolosoA/AGBSolucoes.git && cd AGBSolucoes && sudo chmod +x install.sh && ./install.sh
```

