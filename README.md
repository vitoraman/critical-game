# Critical

Jogo arcade em 2D feito em Lua para o Picotron.

O objetivo é pegar as bolinhas verdes enquanto desvia dos vírus vermelhos que ficam rebatendo na tela. A cada bolinha coletada, mais vírus aparecem e a velocidade deles aumenta com o tempo.

<video src="Introducao.mp4" controls="controls" width="100%">
  O teu navegador não suporta a tag de vídeo.
</video>

### Autores

Projeto desenvolvido para a disciplina de Engenharia de Software 2.

- Eduardo Sá
- Isaías da Silva
- Pablo Felipe
- Vitor Amâncio

## Como jogar

- **Bolinhas verdes:** Pegue para ganhar pontos.
- **Vírus vermelhos:** Não encoste neles com o personagem azul, senão é Game Over.
- **Dash:** Use para dar uma arrancada rápida e escapar quando ficar encurralado.
- **Overdrive:** Colete 5 bolinhas seguidas sem deixar a barra de combo zerar. Quando ativa, os vírus ficam verdes e vulneráveis — encoste neles para destruí-los e somar mais pontos.


## Controles

| Ação | Teclado | Controle |
| :--- | :--- | :--- |
| **Mover** | Setas direcionais/WASD | Analógico / D-Pad |
| **Dash** | Tecla `Z` ou `ESPAÇO` | Botão `B` |
| **Iniciar / Reiniciar** | Tecla `Z` ou `ESPAÇO` | Botão `B` |

---

## Download (Windows, Linux e Mac)

Você pode baixar os executáveis já prontos na aba de **[Releases](../../releases)**:

### Windows
1. Baixe o `.zip` da versão Windows.
2. Extraia os arquivos e abra o `critical.exe`.

### Linux
1. Baixe o pacote para Linux e extraia.
2. Dê permissão e execute:
   ```bash
   chmod +x critical
   ./critical
   ```

### macOS
1. Baixe o pacote `.zip` para Mac e extraia.
2. Abra o aplicativo `critical.app` (se o macOS bloquear por ser aplicativo de desenvolvedor não verificado, libere em *Ajustes do Sistema > Privacidade e Segurança*).

---

## 🌐 Jogar online

Se preferir não baixar nada, o jogo roda direto pelo navegador:

**[Jogar no navegador](https://pablosantostl.github.io/trabalho-eds2/)**

---

## Rodando no Picotron

Caso você tenha o Picotron instalado e queira rodar o código direto:

1. Clone o repositório:
   ```bash
   git clone https://github.com/vitoraman/critical-game.git
   ```
2. No console do Picotron, abra a pasta e digite:
   ```text
   load critical.lua
   run
   ```
