# Cybersecurity Labs

Repositório onde documento, em formato de writeup, os laboratórios práticos de cibersegurança que venho realizando por conta própria — como parte da minha jornada de estudo e preparação para atuar na área, com foco em análise/SOC N1.

Cada lab é feito em ambiente controlado (máquinas virtuais próprias), documentado com metodologia, evidências (screenshots) e análise do que foi observado — não só o "como fazer", mas o raciocínio por trás de cada etapa.

##  Ambiente utilizado

| Máquina | Função |
|---|---|
| Kali Linux | Máquina de ataque / análise |
| Linux Mint | Host alvo |

Ambas rodando em VirtualBox, em rede local isolada.

##  Labs

| # | Nome | Categoria | Descrição |
|---|---|---|---|
| 001 | [Who Is There?](LAB-001-Who-Is-There) | Network Recon / Enumeração | Reconhecimento de host na rede, identificação de porta e serviço não documentado, correlação com processo local. |
| 002 | [Log Analysis](LAB-002-Log-Analysis) | Log Analysis / Detecção | Simulação de força bruta via SSH, identificação do padrão de ataque em `/var/log/auth.log` e contenção via `ufw`. |
| 003 | [The Exposed Service](LAB-003-The-Exposed-Service) | Network Recon / Service Enumeration | Enumeração aprofundada de um serviço SSH exposto: versão, banner e algoritmos criptográficos suportados. |
| 004 | [Vestígios de um Acesso](LAB-004-Forense-Leve) | Forense Leve / IR | Investigação de um acesso local simulado, reconstrução de timeline a partir de múltiplas fontes de evidência (histórico de comandos, logs de login, sistema de arquivos). |

> Novos labs são adicionados conforme avançam os estudos — a tabela acima é atualizada a cada publicação.

##  Objetivo

Construir, de forma prática e documentada, uma base de experiência em reconhecimento de rede, detecção de intrusão, análise de log e resposta a incidentes — habilidades centrais para atuação como analista SOC nível 1.

##  Escopo e segurança

Todos os laboratórios são realizados exclusivamente em ambiente próprio e controlado (máquinas virtuais locais), sem qualquer interação com sistemas de terceiros. Finalidade estritamente educacional.
