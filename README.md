# Enteroparasitos em Foco

Site didático de parasitologia humana para a graduação, com foco nos parasitos intestinais. Reúne oito módulos (fundamentos, protozoários, nematoides, cestódeos, esquistossomose, diagnóstico laboratorial, imunologia e epidemiologia), microscópio virtual e uma bancada de exame parasitológico de fezes (EPF).

Realização: LaPaHV (Laboratório de Parasitologia Humana e Veterinária) · UFRN.

## Arquivos

| Arquivo | Para que serve |
| --- | --- |
| `index.html` | O site inteiro (texto, estilos, scripts e logos embutidos) |
| `favicon.svg` | Ícone da aba do navegador |
| `_headers` | Cabeçalhos de segurança e de cache usados pelo Cloudflare Pages |
| `.gitignore` | Arquivos do sistema que o Git deve ignorar |

O site não precisa de compilação nem de servidor. As fontes vêm do Google Fonts; sem internet, o navegador usa fontes do sistema.

## Publicar no Cloudflare Pages a partir do GitHub

1. Crie um repositório no GitHub (por exemplo, `enteroparasitos-em-foco`) e envie estes arquivos para a raiz dele.
2. No painel do Cloudflare: **Workers & Pages → Criar → Pages → Conectar ao Git** e escolha o repositório.
3. Em **Configurações de build**: predefinição de framework **Nenhuma**, comando de build **vazio**, diretório de saída `/`.
4. Clique em **Salvar e implantar**. O endereço fica no formato `https://<nome-do-projeto>.pages.dev`.

Cada novo commit na branch principal publica a atualização automaticamente.

## Observações

- Previsões e progresso dos alunos ficam salvos só no navegador de cada um (localStorage); nada é enviado a servidores.
- Casos clínicos são fictícios. Tratamentos aparecem apenas em nível didático, sem doses.
- Ilustrações são esquemas originais desenhados a partir das medidas de referência; simuladores são modelos didáticos.
