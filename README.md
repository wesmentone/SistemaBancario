<h1 align="center">🏦 Sistema Bancário em Python</h1>

<p align="center">
Simulação de operações bancárias desenvolvida em Python para prática de lógica de programação.
</p>

<hr>

<h2>📌 Sobre o Projeto</h2>

<p>
Este projeto consiste em um sistema bancário simples desenvolvido em <b>Python</b>,
executado diretamente no terminal (CLI).
</p>

<p>
O sistema permite que o usuário realize operações bancárias básicas como
<b>saques, depósitos e consulta de saldo</b>.
</p>

<p>
O objetivo do projeto é reforçar conceitos fundamentais da programação,
como controle de fluxo, estruturas condicionais e validação de dados.
</p>

<hr>

<h2>⚙️ Tecnologias Utilizadas</h2>

<table>
<tr>
<th>Tecnologia</th>
<th>Descrição</th>
</tr>

<tr>
<td>Python</td>
<td>Linguagem utilizada para desenvolvimento da aplicação.</td>
</tr>

<tr>
<td>CLI (Terminal)</td>
<td>Interface baseada em linha de comando para interação com o usuário.</td>
</tr>

<tr>
<td>Lógica de Programação</td>
<td>Uso de variáveis, condicionais e controle de fluxo.</td>
</tr>

</table>

<hr>

<h2>🧩 Funcionalidades</h2>

<table>
<tr>

<td align="center">

<h3>💸 Saque</h3>

Permite retirar valores da conta respeitando limite diário e valor máximo por operação.

</td>

<td align="center">

<h3>💰 Depósito</h3>

Permite adicionar saldo à conta, validando valores positivos.

</td>

<td align="center">

<h3>📄 Extrato</h3>

Exibe o saldo atual e a quantidade de saques realizados.

</td>

</tr>
</table>

<hr>

<h2>📊 Regras do Sistema</h2>

<table>

<tr>
<th>Regra</th>
<th>Descrição</th>
</tr>

<tr>
<td>Saldo inicial</td>
<td>R$ 1500.00</td>
</tr>

<tr>
<td>Limite de saques</td>
<td>3 saques por dia</td>
</tr>

<tr>
<td>Valor máximo por saque</td>
<td>R$ 500.00</td>
</tr>

<tr>
<td>Depósitos</td>
<td>Apenas valores positivos são permitidos</td>
</tr>

</table>

<hr>

<h2>📋 Menu do Sistema</h2>

<pre>
[1] Sacar
[2] Extrato
[3] Depósito
[0] Sair
Digite a opção desejada:
</pre>

<hr>

<h2>💻 Código do Projeto</h2>

<pre>
saldo = 1500.0
LIMITE_SAQUE = 3
saques_realizados = 0

opcion = int(input("[1] Sacar
[2] Extrato
[3] Depósito
[0] Sair
Digite a opção desejada: "))
</pre>

<hr>

<h2>🧠 Melhorias Possíveis no Código</h2>

<table>

<tr>
<th>Melhoria</th>
<th>Benefício</th>
</tr>

<tr>
<td>Uso de funções</td>
<td>Separar saque, depósito e extrato em funções para melhorar organização do código.</td>
</tr>

<tr>
<td>Loop do sistema</td>
<td>Permitir que o programa continue executando até o usuário escolher sair.</td>
</tr>

<tr>
<td>Tratamento de erros</td>
<td>Utilizar try/except para evitar erros quando o usuário digitar valores inválidos.</td>
</tr>

<tr>
<td>Histórico de transações</td>
<td>Registrar todas as operações realizadas.</td>
</tr>


<h2>📚 Conceitos de Programação Aplicados</h2>

<ul>

<li>Variáveis e constantes</li>

<li>Estruturas condicionais (if / elif / else)</li>

<li>Controle de fluxo</li>

<li>Entrada de dados via terminal</li>

<li>Validação de regras de negócio</li>

</ul>

<hr>

<p align="center">

