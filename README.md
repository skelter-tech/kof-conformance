# kof-conformance

Suíte de conformidade e teste diferencial **independente e não oficial** para a
linguagem [Kof](https://github.com/KofLang/Kof4j).

> ⚠️ Este projeto **não tem vínculo** com a autora da linguagem Kof nem com a
> organização KofLang. Não é endossado, mantido ou revisado por ela. Qualquer
> divergência encontrada aqui é uma observação desta suíte, não uma posição
> oficial do projeto Kof.

## Objetivo

- Reunir casos de teste que descrevem o comportamento esperado da linguagem.
- Executar o mesmo programa em diferentes alvos (JVM, nativo, script, web) e
  comparar os resultados (teste diferencial).
- Gerar relatórios reprodutíveis que possam, se úteis, ser reportados
  educadamente ao projeto upstream.

## Estrutura

| Pasta       | Conteúdo                                           |
|-------------|----------------------------------------------------|
| `cases/`    | Programas Kof usados como casos de teste           |
| `expected/` | Saídas esperadas para cada caso                    |
| `runner/`   | Scripts que executam os casos e comparam resultados|
| `reports/`  | Relatórios gerados pelas execuções                 |

## Licença

GPLv3 — veja [LICENSE](LICENSE).
