# pomodoro-em-c
Criei meu próprio Timer Pomodoro em C para focar nos estudos sem distrações. Em vez de apps pesados ou abas cheias de anúncios, desenvolvi uma ferramenta leve que roda direto no terminal. É a união da lógica de baixo nível com a produtividade real: rápido, simples e eficiente.


Pomodoro Timer CLI

Este projeto consiste em uma ferramenta de gestão de tempo baseada na Técnica Pomodoro, desenvolvida integralmente em linguagem C. O objetivo foi criar uma solução de alta performance e baixo consumo de recursos que opere diretamente via interface de linha de comando (CLI), eliminando as distrações comuns em aplicações gráficas ou baseadas em navegadores.
Objetivo do Projeto

O foco principal deste desenvolvimento foi a aplicação de conceitos de programação de baixo nível para resolver um problema de produtividade. A aplicação permite que o utilizador defina uma tarefa específica e um período de tempo, fornecendo um acompanhamento visual contínuo até a conclusão do ciclo.
Características Técnicas

    Feedback Visual em Tempo Real: Implementação de uma barra de progresso dinâmica que utiliza buffers de saída para atualização na mesma linha, evitando redundância de dados no terminal.

    Precisão de Cronometragem: Utilização da função usleep para garantir atualizações suaves da interface a cada 0.5 segundos, demonstrando controlo sobre o fluxo de execução.

    Portabilidade e Eficiência: Código otimizado para execução rápida com footprint de memória virtualmente nulo.

    Sinalização de Sistema: Uso de caracteres de escape para emitir alertas sonoros diretamente através do hardware do sistema ao finalizar o processo.

Implementação

O código demonstra o domínio de competências fundamentais em C, tais como:

    Manipulação de strings e entrada de dados formatada.

    Lógica aritmética para conversão de unidades de tempo (segundos para formato MM:SS).

    Gestão de loops de eventos e atualização de interface via stdout.

Instruções de Compilação e Execução

    Compilação:
    Bash

gcc pomodoro.c -o pomodoro

Execução:
Bash

    ./pomodoro

Conclusão

Este projeto evidencia a capacidade de traduzir requisitos funcionais em código limpo e eficiente. A escolha pela linguagem C reflete o interesse em compreender a interação direta com o sistema operativo e a criação de ferramentas robustas que priorizam a funcionalidade e o desempenho.
