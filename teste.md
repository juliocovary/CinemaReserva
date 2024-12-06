<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>História de Usuárias</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            text-align: center;
            padding: 8px;
        }
        th {
            background-color: purple;
            color: white;
        }
    </style>
</head>
<body>
    <h1>1. História de Usuárias</h1>
    <table>
        <thead>
            <tr>
                <th>ID</th>
                <th>História de Usuária</th>
                <th>Critérios de Aceitação</th>
                <th>Prioridade</th>
                <th>RF/RNF relacionado</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>US01</td>
                <td>Como usuária, quero consultar rapidamente a posologia de um medicamento, para obter informações precisas e tomar decisões com agilidade.</td>
                <td>
                    <ol>
                        <li>O sistema deve permitir busca por nome do medicamento.</li>
                        <li>A posologia deve ser exibida de forma clara e detalhada.</li>
                    </ol>
                </td>
                <td>Média</td>
                <td>RF01</td>
            </tr>
            <tr>
                <td>US02</td>
                <td>Como usuária, quero que o sistema calcule automaticamente a dose com base no peso e idade do paciente, para evitar erros manuais e garantir a segurança do tratamento.</td>
                <td>
                    <ol>
                        <li>O sistema deve aceitar idade e peso como entrada.</li>
                        <li>A dose calculada deve ser exibida imediatamente após a entrada dos dados.</li>
                    </ol>
                </td>
                <td>Alta</td>
                <td>RF02</td>
            </tr>
            <tr>
                <td>US03</td>
                <td>Como usuária, quero que o sistema considere ajustes de dose para pacientes pediátricos obesos, para evitar que a dose ultrapasse o limite recomendado para crianças.</td>
                <td>
                    <ol>
                        <li>O sistema deve identificar automaticamente quando o paciente é pediátrico e obeso.</li>
                        <li>Ajustes de dose devem ser feitos e exibidos.</li>
                    </ol>
                </td>
                <td>Alta</td>
                <td>RF03</td>
            </tr>
            <tr>
                <td>US04</td>
                <td>Como usuária, quero registrar informações como idade, peso e condição do paciente (pediátrico ou adulto), para personalizar o cálculo das doses de acordo com o perfil do paciente.</td>
                <td>
                    <ol>
                        <li>O sistema deve aceitar entrada de idade, peso e condição (pediátrico ou adulto).</li>
                        <li>As informações devem ser armazenadas para uso futuro no cálculo.</li>
                    </ol>
                </td>
                <td>Alta</td>
                <td>RF04</td>
            </tr>
            <tr>
                <td>US05</td>
                <td>Como usuária, quero que o sistema sugira automaticamente a forma de apresentação do medicamento (como comprimido ou líquido), para otimizar a administração do tratamento.</td>
                <td>
                    <ol>
                        <li>O sistema deve sugerir a apresentação ideal com base nos dados do paciente.</li>
                        <li>A forma sugerida deve ser destacada.</li>
                    </ol>
                </td>
                <td>Média</td>
                <td>RF05</td>
            </tr>
            <tr>
                <td>US06</td>
                <td>Como usuária, quero visualizar o horário das doses, a quantidade de frações diárias e a duração do tratamento, para planejar e orientar o paciente corretamente.</td>
                <td>
                    <ol>
                        <li>O sistema deve calcular e exibir os horários das doses.</li>
                        <li>Deve indicar a duração total do tratamento e as frações diárias.</li>
                    </ol>
                </td>
                <td>Alta</td>
                <td>RF06</td>
            </tr>
            <tr>
                <td>US07</td>
                <td>Como usuária, quero alterar manualmente o esquema posológico sugerido pelo sistema, para atender a casos específicos que exigem flexibilidade.</td>
                <td>
                    <ol>
                        <li>O sistema deve permitir ajustes manuais no esquema de horários e frações.</li>
                        <li>O sistema deve exibir os ajustes antes de confirmar a alteração.</li>
                    </ol>
                </td>
                <td>Média</td>
                <td>RF07</td>
            </tr>
            <tr>
                <td>US08</td>
                <td>Como usuária, quero que o sistema utilize informações de bulas, guidelines pediátricas e estudos clínicos, para garantir que o cálculo das doses seja seguro e baseado em evidências científicas.</td>
                <td>
                    <ol>
                        <li>O sistema deve mostrar a fonte utilizada para cálculo.</li>
                        <li>Os dados devem estar atualizados conforme as diretrizes mais recentes.</li>
                    </ol>
                </td>
                <td>Alta</td>
                <td>RF08</td>
            </tr>
            <tr>
                <td>US09</td>
                <td>Como administradora do sistema, quero atualizar periodicamente as fontes de dosagem (guidelines, bulas, estudos), para garantir que o sistema reflita as diretrizes mais recentes.</td>
                <td>
                    <ol>
                        <li>O sistema deve permitir o upload de novas diretrizes.</li>
                        <li>O sistema deve exibir a data da última atualização.</li>
                    </ol>
                </td>
                <td>Média</td>
                <td>RF09</td>
            </tr>
            <tr>
                <td>US10</td>
                <td>Como usuária, quero que o sistema exiba a fonte de dosagem utilizada no cálculo, para aumentar a transparência e permitir conferência rápida.</td>
                <td>
                    <ol>
                        <li>O sistema deve exibir a fonte no momento do cálculo.</li>
                        <li>Deve ser possível consultar a fonte diretamente na interface do sistema.</li>
                    </ol>
                </td>
                <td>Alta</td>
                <td>RF10</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
