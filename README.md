# Moldes de Natal

Página de vendas estática dos pacotes Básico e Completo.

## Arquivos

- `index.html`: página com estilos, animações, carrosséis e lógica dos pacotes.
- `assets/`: imagens e vídeos utilizados na página.

Não precisa instalar dependências nem executar build. Publique a raiz deste repositório em uma hospedagem de sites estáticos.

## Configurações

Os três endereços de checkout ficam no objeto `checkouts` do script `upgrade-offer-script`, em `index.html`.
O Pixel Meta está configurado para PageView e InitiateCheckout. Cliques nos botões que apenas levam à seção de pacotes não disparam InitiateCheckout.

Os modelos editáveis e os PDFs de entrega aos clientes não fazem parte deste repositório.
