# WEMIN TV Player

Player para TVs Samsung Tizen 5.5 ou superior. Esta edição vem vazia: não inclui listas, servidores de conteúdo, fontes de eventos ou catálogos predefinidos. Não consulta a conta ou o catálogo remoto do WEMIN TV.

## Como usar

1. Baixe o pacote WGT na [última release](https://github.com/Shicknovz/WEMIN_TV_Player/releases/latest).
2. Instale pelo [Apps2Samsung](https://apps2samsung.com/), com a TV em modo desenvolvedor. O instalador faz a assinatura para sua TV.
3. Na primeira abertura, informe o link da sua lista M3U em Minhas fontes. Use apenas conteúdo que você tem autorização para acessar.
4. Opcionalmente, configure seus próprios endereços-base de canais e filmes no formato de catálogo Saimo. Os campos começam vazios e removê-los não restaura nenhum endereço de fábrica.

Os endereços ficam armazenados no aparelho. Não há fonte de complemento, atualização remota de código ou mecanismo de configuração de conteúdo pelo editor.

## Identidade separada

- Nome: WEMIN TV Player
- Pacote: WeminPlay1
- Aplicativo: WeminPlay1.Player
- Versão: 0.4.0

Pode coexistir com o WEMIN TV original. A edição original com fontes configuradas é distribuída separadamente e não deve ser usada como pacote desta edição.

## Validação

Passou na checagem TypeScript, geração ES5, cinco testes automatizados de fontes e conferência visual de primeira abertura em navegador 1920×1080. Os testes verificam ausência de requisições de conteúdo sem fontes, uso de M3U independente, remoção de fontes e ausência dos provedores anteriores no bundle. O teste desta edição em uma TV física ainda está pendente; o teste anterior da 0.3.3 refere-se à edição original.

## Créditos e licenças

Inclui código derivado do [Saimo TV / Saimo-Site](https://github.com/SaimoTV/Saimo-Site), sob MIT, Copyright (c) 2025-2026 Saimo TV. A licença e os avisos das bibliotecas estão em THIRD-PARTY-NOTICES.txt dentro do WGT e no anexo da release. As alterações do WEMIN TV Player não têm código-fonte publicado neste repositório de distribuição.

## Redistribuição

O responsável pelo WEMIN TV Player autoriza Apps2Samsung e tizen-community-packages a redistribuir os pacotes desta edição publicados nas Releases deste repositório, preservando créditos e licenças. Esta permissão não se estende a conteúdos de terceiros.
