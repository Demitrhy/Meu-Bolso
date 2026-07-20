# MeuBolso 💰

**Aplicativo pessoal de planejamento de gastos e metas — feito para o iPhone.**

O MeuBolso ajuda você a enxergar, num lugar só, quanto ganha, quanto gasta, o que
já pagou, o que ainda falta pagar no mês e quanto tempo falta pra realizar um sonho
(como comprar um MacBook). Simples, bonito e no estilo do iOS.

---

## 🎯 Para que serve

- Saber o **saldo previsto do mês** (quanto sobra depois de pagar tudo).
- Controlar os **próximos pagamentos** e o que **já foi pago**.
- Ver **para onde vai o seu dinheiro** (gastos por categoria).
- Criar **metas de economia** e descobrir em quantos meses você chega lá.

---

## 📱 Funcionalidades

### Resumo
- Card de **Saldo previsto** do mês (fica **verde/azul** no positivo e **vermelho** no negativo).
- **Renda · Gastos · % pago**, com barra de progresso de pagamento.
- **Já paguei** (verde) × **Falta pagar** (amarelo).
- Gráfico **"Pra onde vai o dinheiro"** — gastos por categoria, com valores e %.
- Lista dos **próximos pagamentos** e prévia da sua **meta**.

### Gastos
- Barra de meses (mês atual + 3 à frente).
- Lista agrupada e recolhível: **A pagar** e **Deu certo** (pagos).
- Cada conta mostra ícone colorido por categoria, nome, vencimento e valor.
- Dois tipos de gasto:
  - **Único** — vale só no mês em que foi lançado (ex.: uma compra).
  - **Fixo mensal** — repete todo mês automaticamente (ex.: aluguel, internet, Netflix); você marca "pago" mês a mês.
- **Adicionar / editar / excluir** e **marcar como pago** com um toque.

### Metas
- Cada meta com **anel de progresso** (% concluído).
- Cálculo automático: *"Faltam R$ X · ≈ N meses"*, usando a sobra do mês.
- Botão **"Guardar dinheiro"** pra ir somando o que você separou.

### Seus dados
- **Exportar backup** (gera um arquivo `.json`) e **Restaurar backup**.
- **Apagar tudo** pra recomeçar.

---

## 🔒 Privacidade e onde ficam os dados

Tudo fica **salvo no próprio aparelho** (no `localStorage` do navegador), **offline**.
Nada vai para a nuvem, para servidores ou para a internet. Cada pessoa que instala
tem seus **próprios dados, privados**, no celular dela.

> Como os dados ficam só no aparelho, é recomendável **exportar um backup de vez em
> quando** (guardar em Arquivos ou no e-mail) para não perder se trocar de celular.

---

## 🛠️ Tecnologia

- **Web App (PWA)** — um único arquivo `index.html` (HTML + CSS + JavaScript puro), sem
  frameworks e sem instalação de dependências.
- Visual estilo **iOS**, com **modo claro e escuro** automáticos.
- Idioma **português (BR)**, valores em **Real (R$)**.
- Funciona **offline**; dados no `localStorage`.

---

## 📲 Como instalar no iPhone 11

1. Hospede o `index.html` (recomendado: **Netlify** ou **GitHub Pages**, para ter um
   endereço fixo e conseguir atualizar depois).
2. Abra o endereço no **Safari**.
3. Toque em **Compartilhar** ↑ → **Adicionar à Tela de Início**.
4. Pronto — o ícone 💰 aparece na tela inicial e abre em tela cheia, como um app.

Atualizar depois é fácil: sobe o novo `index.html` no mesmo endereço, abre o app e ele
carrega a versão nova — **sem perder seus dados**. Para conferir, o número da **versão**
aparece no rodapé do Resumo.

---

## 📁 Arquivos do projeto

| Arquivo | O que é |
|---|---|
| `index.html` | **O app** (é este que você hospeda e instala). Começa vazio. |
| `meubolso-preview.html` | Versão de demonstração (com dados de exemplo) usada para visualizar. |
| `README.md` | Este documento. |

---

## 📌 Versão

**1.0.0** — primeira versão completa (Resumo, Gastos, Metas, Backup).

*Feito com carinho para uso pessoal.* 💙
