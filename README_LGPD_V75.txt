RODA DAS COMPETÊNCIAS — LGPD | ESTRUTURA XXI V75 CORRIGIDA

BASE FUNCIONAL: RODA_XXI_V75_PENTAGONO_CORRIGIDO.zip.
Esta é a V75 corrigida do Projeto XXI, adaptada integralmente para o conteúdo LGPD.

LAYOUT E NAVEGAÇÃO
- Tela de entrada LOGIN.jpg aprovada (Laboratório de Cidadania Digital, LGPD).
- TRÊS ÁREAS CLICÁVEIS INVISÍVEIS SOBRE A ARTE: experiência individual, coletiva e instruções de uso.
- Controle de tela cheia na entrada e no interior da aplicação. Nos navegadores compatíveis, selecionar a modalidade solicita tela cheia no próprio clique.
- Painel de Controle V75, gestão de turmas, roda, pergunta, pentágono e intervenção com a mesma organização da versão XXI V75.
- Layout da experiência coletiva igual ao individual na roda e no pentágono (V75).
- A modalidade individual registra SIM/NÃO; a coletiva, de 0 até o total da turma.

CONTEÚDO PEDAGÓGICO PRESERVADO
- 20 perguntas LGPD originais (4 em cada eixo), com as pontes de mediação e de encaminhamento intactas.
- Intervenções individuais/coletivas LGPD conforme banco_intervencoes.json original.
- Pentágono calcula RESPOSTAS PROTETIVAS: em perguntas protetivas SIM conta SIM; em perguntas protetivas NÃO conta total menos SIM.
- Sem respostas, traço (—) em vez de 0%. Resposta 0 SIM é válida.

PERSISTÊNCIA / COMPATIBILIDADE
- Usa as mesmas chaves da LGPD anterior: rodaLGPDPremiumV10, rodaLGPDTurmasV10, rodaLGPDSelectedClass.
- A lógica V75 salva os registros coletivos no registro único da turma e usa os dados ativos no painel.
- Recomendamos EXPORTAR DADOS (JSON) antes da substituição. Armazenamento é local ao navegador.

PUBLICAÇÃO NO GITHUB
Substitua TODOS os arquivos da raiz pelos do ZIP. Imagens e arquivos HTML, CSS, JavaScript e JSON ficam na raiz, com os nomes mantidos. Atualize com Ctrl+F5.
