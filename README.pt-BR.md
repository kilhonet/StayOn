# StayOn

**Ferramenta gratuita para Windows que mantém a tela e o PC acordados: basta clicar no gatinho da área de trabalho.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/stayon?lang=pt)

![Tela do StayOn](images/stayon-ko.webp)

> A interface do programa não tem tradução para português; ela é exibida em inglês. Os nomes de menu abaixo aparecem como na tela.

## Visão geral

Você provavelmente já passou por isso: uma apresentação aberta, um download longo em andamento ou um documento sendo lido — e, minutos depois, a tela apaga e o PC dorme. Em um PC de empresa, muitas vezes nem é possível mudar as configurações de energia.

O StayOn coloca um gatinho em pixel art no canto da área de trabalho. **Clique no gato dormindo e ele acorda**; enquanto o gato estiver acordado, a tela não apaga e o PC não entra em suspensão. Clique de novo e o gato volta a dormir; tudo retorna ao normal.

As configurações de energia e suspensão do Windows não são tocadas. O efeito só existe enquanto o programa está em execução, e nada fica para trás ao sair ou reiniciar. Um único arquivo, com menos de 100 KB.

## Principais recursos

- **Um clique** — Clique no gato para ligar ou desligar a prevenção de suspensão. O menu do botão direito também funciona.
- **Impede o apagamento da tela, a suspensão e o bloqueio** — Protetor de tela, desligamento da tela, modo de suspensão e bloqueio automático não são acionados. Também impede que mensageiros como o Teams mostrem você como "Ausente".
- **Sem alterar as configurações do Windows** — Opções de energia e políticas de grupo ficam intactas. Não precisa de permissão de administrador.
- **Um gato para colocar onde quiser** — Arraste-o para onde preferir; a posição é lembrada. Ele não sai da tela.
- **Tamanho 100 % · 200 % · 400 %** — Escolha o tamanho do gato conforme o monitor. Nítido até em telas de alta resolução (HiDPI).
- **Executar ao iniciar** — O gato aparece junto com o Windows (versão com instalador).
- **Leve e simples** — Reescrito em C: executável de 83 KB, sem assistente de instalação nem janela de configurações. Sempre no topo, mas nunca na barra de tarefas ou na lista Alt+Tab.
- **7 idiomas** — Coreano · inglês · japonês · chinês · russo · italiano · francês. Segue o idioma de exibição do Windows.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Download](https://down.kilho.net/stayon?lang=pt) |
| Portátil (ZIP) | [Download](https://down.kilho.net/stayon?lang=pt&nosetup) |

Com o instalador, o gato aparece assim que a instalação termina. Na versão portátil, descompacte o ZIP e execute `StayOn.exe`.

Diferença entre as versões: **Run at boot** só pode ser ativado na versão com instalador (na portátil, o item de menu fica acinzentado).

## Como usar

### Primeiros passos

1. Abra o StayOn. Um **gato dormindo** aparece no canto inferior direito da tela, logo acima da barra de tarefas.
2. **Clique** no gato. Ele se espreguiça e acorda; a partir daí a tela não apaga e o PC não dorme.
3. Faça o seu trabalho. O gato fica na tela enquanto estiver acordado.
4. Ao terminar, **clique no gato de novo**. Ele volta a dormir e as configurações de suspensão retornam ao normal.

Ao iniciar o programa, o gato **sempre começa dormindo**. Mesmo que você o tenha deixado acordado ontem, ele não liga sozinho na próxima execução — assim a tela nunca fica acesa sem que você queira.

### Organização da tela

Não há janela nem tela de configurações: só o gato e o seu **menu do botão direito**.

| Menu | O que faz |
|---|---|
| **Run** / **Stop** | Liga/desliga a prevenção de suspensão — o mesmo que clicar no gato |
| **Size** › 100% · 200% · 400% | Tamanho do gato. Padrão 200% |
| **Run at boot** (marcado) | Início automático com o Windows (versão com instalador) |
| **Crafted by Kilho** | Abrir o site |
| **Exit** | Encerrar o programa — a prevenção de suspensão também é desligada |

- **Gato dormindo** = prevenção desligada, **gato acordado** = prevenção ligada. Não precisa de outro indicador: o gato mostra.
- **Arrastar para mover** — Segure o gato e arraste. Um movimento mínimo conta como clique.

### O que fazer quando…

**Manter a tela acesa durante uma apresentação ou reunião**
Clique uma vez no gato para acordá-lo antes de abrir os slides. Ao terminar, clique de novo. Não é preciso mexer nas configurações de energia do projetor nem do PC da sala.

**Deixar um download ou tarefa longa rodando enquanto se ausenta**
Acorde o gato e o PC não dorme na sua ausência, então a tarefa continua. Ao voltar, é só fazer o gato dormir. Isso não tem relação com desligar o PC — desligue você mesmo quando a tarefa acabar.

**Teams · Slack fica me colocando como "Ausente"**
Se você só lê ou ouve uma reunião sem mexer o mouse, os mensageiros marcam você como ausente. Com o gato acordado, isso não acontece.

**Não consigo mudar as configurações de energia no PC da empresa**
O StayOn não altera as configurações do Windows nem usa permissão de administrador. Mesmo em um PC com o tempo de desligamento da tela fixado por política de grupo, a tela fica acesa enquanto o gato está acordado.

**O gato atrapalha**
- **Arraste-o** para onde quiser. A posição é lembrada.
- Botão direito → **Size** → **100%** e ele quase não aparece.
- O gato não pode ser empurrado para fora da tela; ele para na borda do monitor.

**O gato é pequeno demais (monitor 4K etc.)**
Botão direito → **Size** → **400%**. O valor é multiplicado pela escala do Windows, então fica nítido em qualquer resolução.

**Fazer o gato aparecer sempre que o PC liga**
Na versão com instalador, botão direito → marque **Run at boot**. A partir da próxima inicialização, o gato aparece dormindo após o logon. Na versão portátil esse item fica bloqueado — use a versão com instalador.

**Não vejo o gato**
- Se já estiver em execução, abrir de novo não faz nada (só um gato por vez). Verifique os cantos da tela e os outros monitores.
- Se a configuração de monitores mudou e a posição salva ficou fora da tela, ele volta automaticamente à posição padrão (canto inferior direito do monitor principal).

**Fechar o StayOn por completo**
Botão direito → **Exit**. Se o gato estava acordado, a prevenção de suspensão é desligada junto. Se você só fizer o gato dormir, o programa continua aberto para acordá-lo de novo na hora.

**Verificar se a prevenção de suspensão está funcionando**
Se o gato está acordado, está funcionando. Para ter certeza, espere passar o tempo de desligamento da tela em Configurações do Windows → Sistema → Energia e veja que a tela continua acesa.

**Usar a mesma posição e tamanho em outro PC**
As configurações ficam na sua conta de usuário e são mantidas nas atualizações. Em um PC novo, mova o gato uma vez e escolha um tamanho; a partir daí fica lembrado.

## Configuração

Não há janela de configurações; tudo é alterado no menu do botão direito e salvo na hora.

| Item | Padrão |
|---|---|
| Size | 200% |
| Posição do gato | Canto inferior direito do monitor principal (acima da barra de tarefas) |
| Run at boot | Desligado |
| Estado da prevenção de suspensão | Não é salvo — sempre começa dormindo |

O idioma da interface segue o idioma de exibição do Windows (coreano · inglês · japonês · chinês · russo · italiano · francês; nos demais casos, inglês).

## Requisitos

- Windows 10 ou Windows 11 (32 e 64 bits)
- Não requer permissão de administrador nem runtime adicional.
- A conexão com a Internet é usada apenas para verificar avisos de nova versão. Funciona offline.

## Atualizações

O StayOn **não** se atualiza sozinho. Ao iniciar, verifica se há uma versão nova e mostra um aviso; ao pressionar **Yes**, a página de download é aberta e o programa é encerrado. As novas versões são publicadas manualmente após verificação interna e anunciadas na [página do StayOn](https://kilho.net/stayon). Veja o [aviso sobre a política de atualização](https://en.kilho.net/archives/notice/2940).

## Licença

O StayOn é **freeware**. Use gratuitamente e sem restrições em qualquer lugar — empresa, casa, órgãos públicos, escola — e redistribua livremente.

## Links

- Site: <https://kilho.net/stayon>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
