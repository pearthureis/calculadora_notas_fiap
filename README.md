Calculadora de Média Semestral

Este projeto consiste em uma aplicação simples em Python para cálculo da média semestral de um aluno, considerando diferentes componentes avaliativos.

Funcionalidades
Entrada de notas para:
3 Checkpoints (CP1, CP2, CP3)
2 Sprints
Global Solution (GS)
Validação de dados (notas devem estar entre 0 e 10)
Desconsideração automática da menor nota entre os Checkpoints
Cálculo da média semestral:
Média parcial com peso de atividades contínuas
Peso final considerando o Global Solution
Regras de Cálculo
A menor nota entre os Checkpoints é descartada
A média dos componentes contínuos corresponde a 40% da nota final
A Global Solution corresponde a 60% da nota final
Fórmula Utilizada

Média contínua:

(cp1 + cp2 + cp3 - menor_cp + sprint1 + sprint2) / 4

Média final:

(média_contínua * 0.4) + (gs * 0.6)
Como Executar
Certifique-se de ter o Python instalado (versão 3.x)
Execute o arquivo no terminal:
python pcp_1sem_cp2_ex03.py
Insira as notas conforme solicitado
Observações
O programa reinicia automaticamente caso algum valor inválido seja inserido
A interface é baseada em terminal (CLI)
O código pode ser adaptado para interface gráfica ou web futuramente
Melhorias Futuras
Evitar recursividade no tratamento de erros
Melhorar organização do código (funções separadas)
Criar interface gráfica ou versão web
Armazenamento de resultados
