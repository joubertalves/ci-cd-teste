Qual é a principal diferença prática entre CI e CD?

CI (Integração Contínua) é focado em testar, validar e construir artefatos. CD (Entrega/Implantação Contínua) é focado em levar esse artefato testado para um ambiente de usuários (como o GitHub Pages).

O que aconteceria se o teste falhasse antes do deploy?	

O job deploy não seria executado devido à condição needs: test e if: success(), impedindo que código quebrado fosse publicado.

Como a entrega contínua aumenta a confiança do time no processo?	

Reduz o risco com deploys pequenos e frequentes, fornece feedback imediato sobre o estado do código e elimina erros manuais com automação consistente.
