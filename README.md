<h1 align="center">OtPokemon Check</h1>

<p align="center">
  Bot de automação por <b>visão de tela</b> para o jogo <b>OtPokemon</b>. Ao rodar, ele
  lê as mensagens do chat e a posição do player, identifica situações e executa ações
  automáticas — respostas programáveis, movimentação e logout/login em ciclo.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyAutoGUI-2C3E50" alt="PyAutoGUI">
  <img src="https://img.shields.io/badge/tipo-estudo-informational" alt="Estudo">
</p>

---

## Sobre

Projeto de **estudo** criado para entender, na prática, automação por reconhecimento de
tela com a biblioteca **PyAutoGUI**: leitura de regiões da tela, detecção de padrões e
simulação de teclado/mouse. O objetivo é compreender melhor o funcionamento do jogo e
explorar técnicas de automação — não há intenção de uso abusivo.

## O que faz

- **Lê as mensagens** do chat e reage com respostas programáveis.
- **Checa a posição** do player e realiza movimentos automáticos.
- **Executa em loop**: após agir, faz logout e volta depois de um tempo definido.

## Como executar

### Pré-requisitos

- [Python](https://www.python.org/)
- Biblioteca **PyAutoGUI** (e as demais listadas nas importações)
- O jogo **OtPokemon** aberto

### Passos

```bash
git clone https://github.com/GenilsonJrs/otpokemon-check.git
cd otpokemon-check
pip install pyautogui
```

Ajuste as preferências e coordenadas de acordo com a sua resolução/janela do jogo e
execute:

```bash
python chat.py
```

## Aviso

Ferramenta desenvolvida exclusivamente para fins educacionais e de estudo de automação.
Use por sua conta e risco e respeite os termos de serviço do jogo.

## Autor

[Genilson Junior](https://github.com/GenilsonJrs)
