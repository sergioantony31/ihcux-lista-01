# ihcux-lista-01

grupo 
sergio antonio 
Paulo André
Miguel Oliveira 
Lucas Gonçalves 


É a estrutura principal do programa.

class Program
{
}

👉 Tudo em C# precisa estar dentro de uma classe.
👉 Aqui é como se fosse a “caixa” onde o programa existe.

▶️ 2. static void Main()

É o ponto de partida do programa.

static void Main()
{
}

👉 Tudo começa aqui quando você executa o programa.
👉 É como o “botão de ligar”.

🔁 3. while (true)

É uma estrutura de repetição (loop).

while (true)
{
}

👉 Significa: repita para sempre
👉 Só para quando aparece um break ou return

💡 No seu código, serve para:

continuar pedindo dados até o usuário acertar
🔀 4. if

É uma estrutura de decisão.

if (entrada == "cancelar")
{
    return;
}

👉 Traduzindo:

SE acontecer algo → faça isso

Outros exemplos:

if (codigo < 1 || codigo > 10)

👉 Aqui verifica se o número está fora do intervalo

🔄 5. continue

Serve para voltar para o início do loop

continue;

👉 Usado quando:

o usuário erra algo
o programa pede novamente
⛔ 6. break

Serve para sair do loop

break;

👉 Quando o valor está correto, ele sai do while

🛑 7. return

Serve para encerrar o programa

return;

👉 No seu caso:

quando o usuário digita "cancelar"
🔢 8. int.TryParse()

Serve para converter texto em número com segurança

int.TryParse(entrada, out codigo)

👉 Evita erro se o usuário digitar letra
👉 Retorna:

true → deu certo
false → erro
🖥️ 9. Console.WriteLine() e Console.ReadLine()
Entrada:
Console.ReadLine();

👉 Lê o que o usuário digitou

Saída:
Console.WriteLine("Texto");

👉 Mostra mensagem na tela
O programa funciona assim:

Mostra o passo → usuário digita algo
Usa if para verificar se está certo
Se estiver errado → continue (repete)
Se estiver certo → break (avança)
Se cancelar → return (encerra tudo)


Dica importante

Essas são as estruturas básicas da programação:

Sequência → código roda linha por linha
Decisão (if) → escolhe caminhos
Repetição (while) → repete ações
