<div align="center">

<img src="https://github.com/grana-amiga/Mobile-Application-Development/blob/70048aa531d9703bfbd9ede5df5aa9b28a72379c/assets/images/mascot.png" alt="Amiguinho, mascote do Grana Amiga" width="120" /> 

# Grana Amiga

**Educação e organização financeira para quem mais precisa, explicada do jeito mais simples possível.**

Flutter · Android · iOS &nbsp;|&nbsp; CitizenTech · FIAP

</div>

---

## 💡 A ideia

Milhões de famílias brasileiras controlam o dinheiro de cabeça ou em um caderno. Sem informação clara, as contas atrasam, o cartão vira bola de neve e o fim do mês chega antes do dinheiro.

O **Grana Amiga** é um app que ensina e organiza as finanças da casa com **ícones, áudio, letras grandes e linguagem do dia a dia**, pensado para **chefes de família com baixa escolaridade** em famílias de baixa renda. Nada de planilha, nada de "juros compostos": o app mostra, em cores e figuras, se o mês está tranquilo ou apertado, e transforma o aprendizado em jogo.

## 🎯 Proposta

> Dar a cada família um "amigo" que explica o dinheiro sem julgar.

1. **Aprender brincando**: jogos curtos que ensinam conceitos como necessidade x desejo, orçamento, parcelas e mitos sobre dinheiro.
2. **Enxergar o mês**: o *Termômetro do Dinheiro* mostra de relance quanto da renda já foi comprometido.
3. **Registrar sem esforço**: um gasto em três toques, com figuras e teclado numérico grande, ou por conversa no estilo WhatsApp.
4. **Sair do aperto**: um plano de quitação que mostra qual dívida pagar primeiro (a de maiores juros) e quando vence a próxima parcela.
5. **Evitar sustos**: alertas de vencimento e acompanhamento do gasto de luz.

## ✨ Diferenciais

| Diferencial | Como aparece no app |
|---|---|
| **Acessibilidade de verdade** | Botão "Ouvir" lê saldo, dívidas e alertas em voz alta; tamanho da letra ajustável; áreas de toque grandes; contraste alto. |
| **Nunca só cor** | O Termômetro e os alertas combinam **cor + ícone + texto**, para quem tem daltonismo ou dificuldade de leitura. |
| **Experimente antes de entrar** | A tela inicial e os jogos são abertos: dá para jogar antes de criar conta. |
| **Educação que não parece aula** | 5 jogos rápidos, com pontuação e estrelas que mudam a cada resposta. |
| **Registro por conversa** | Chat simulado: "gastei 30 no mercado" vira um registro, com confirmação. |
| **Plano de quitação inteligente** | Dívidas ordenadas por juros, barra de progresso e próximo vencimento. |
| **Energia em foco** | Custo de luz do mês a partir de um medidor de baixo custo (nesta versão, simulado). |
| **Visual acolhedor** | Paleta "Bolso" (petróleo, pêssego, creme e menta) e o mascote Amiguinho. |

## 📱 Telas

| # | Tela | O que faz |
|---|---|---|
| 1 | **Início** | Boas-vindas com áudio, acessibilidade e carrossel de jogos. |
| 2 | **Jogos** | Simulador com pontuação que muda a cada resposta. |
| 3 | **Login e cadastro** | Telefone e senha, formulário validado, biometria simulada. |
| 4 | **Painel principal** | Termômetro, saldo grande com áudio, feed com ícones e botões Entrada, Saída e WhatsApp. |
| 5 | **Adicionar gasto** | Grade de categorias, teclado numérico, câmera (visual) e confirmação. |
| 6 | **Plano de quitação** | Dívidas por juros, progresso e próximo vencimento. |
| 7 | **Alertas e energia** | Contas a vencer e custo de luz do mês. |
| + | **Chat WhatsApp (simulado)** | Registro de gastos por conversa. |

> 📸 _Adicione aqui os prints do app, por exemplo em `docs/prints/` e referenciados com `![Painel](docs/prints/painel.png)`._

## 🎮 Os 5 jogos

1. **Preciso ou Quero?** Separar o que é necessidade do que é desejo.
2. **Mercado com orçamento.** Fechar a compra sem estourar o limite.
3. **Parcelas e juros.** Entender quanto uma compra parcelada realmente custa.
4. **Cofrinho de metas.** Guardar um pouco de cada vez para alcançar um objetivo.
5. **Mito ou verdade.** Derrubar crenças comuns sobre dinheiro.

## 🧩 Tecnologia

- **Flutter** (Dart 3, Material 3) para Android, iOS e Web com um único código.
- Gerenciamento de estado com `StatefulWidget` e `setState`.
- Navegação por **rotas nomeadas**, com envio de parâmetros e retorno de valores.
- `Form` + `GlobalKey<FormState>` com validação e feedback por `SnackBar`.
- `flutter_tts` para leitura em voz alta, fonte **Nunito** e acessibilidade em primeiro lugar.
- Testes unitários da lógica (formatação de moeda, termômetro, jogos, dívidas e leitura do chat) e teste de fumaça do app.

## 🌍 Impacto e ODS

| ODS | Contribuição |
|---|---|
| **1. Erradicação da pobreza** | Ferramentas para a família organizar a renda e sair do endividamento. |
| **4. Educação de qualidade** | Educação financeira em formato de jogo, para quem lê com dificuldade. |
| **10. Redução das desigualdades** | Acesso gratuito e inclusivo à informação financeira. |

## 🛣️ Visão de futuro

- Chatbot real no **WhatsApp**, com mensagens de texto e de áudio.
- Medidor de energia físico (**Arduino/ESP32**) integrado ao app.
- Conta e dados em servidor, com biometria real.
- Leitura de notas fiscais pela câmera.
- Novos jogos e trilhas de aprendizado por fase da vida (primeiro emprego, filhos, aposentadoria).

> ℹ️ Esta versão é um protótipo funcional: os dados são de exemplo, o login é local, o medidor de energia e o chatbot do WhatsApp são simulados.

## 👥 Integrantes

| Nome | RM |
|---|---|
| Cassio Alexandre Ribeiro de Moraes | 567295 |
| Davi Isac Colin Pereira | 567265 |
| Hugo Souza de Jesus | 568542 |
| Matheus Peres Moraes de Jesus | 567300 |
| Pedro Gonçalves Rodrigues | 567651 |

---

<div align="center">

Projeto acadêmico desenvolvido na **FIAP** · Feito com 💚 para as famílias brasileiras.

</div>
