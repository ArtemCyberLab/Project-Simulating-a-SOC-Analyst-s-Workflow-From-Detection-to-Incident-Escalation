Description:
This project provides a detailed walkthrough of a training platform scenario simulating the tasks of a junior Security Operations Center (SOC) analyst. It covers the full incident response lifecycle: analyzing SIEM alerts, threat verification, containment, and proper escalation. Special attention is given to mapping practical actions to the stages of the Cyber Kill Chain model, demonstrating a deep understanding of both attack and defense processes.

Key Stages and Demonstrated Skills:

1. Detection & Analysis
SIEM Log Analysis: Alerts were analyzed to identify suspicious activity: multiple unauthorized connection attempts and successful SSH (port 22) authentication events from IP address 221.181.185.159.

Threat Verification: The IP was checked using an internal Threat Intelligence tool (ip-scanner.thm), which confirmed with 100% confidence that it was malicious. Information was gathered about its ISP (China Mobile), geolocation (Zhenjiang, China), and associated domain name (chinamobileltd.thm).

2. Containment & Eradication
Immediate Response: The malicious IP was promptly added to the firewall blocklist (firewall.internal) to prevent further communication attempts and contain the threat at the network perimeter.

3. Incident Escalation
Decision-Making: After initial response, the appropriate staff member for escalation was selected. Based on role analysis:

Will Griffin (SOC Team Lead) was chosen as the correct point of escalation, as he is the direct supervisor of SOC analysts and coordinates further investigation actions, aligning with standard operating procedures (SOPs).

4. Theoretical Context: Analysis via the Cyber Kill Chain
Attack Decomposition: The attacker's actions were analyzed according to the Cyber Kill Chain model:

Reconnaissance: The attacker likely conducted preliminary reconnaissance to select a target.

Weaponization: Preparation of malicious payloads or scripts.

Delivery: Attempt to deliver the payload via an SSH attack.

Exploitation: Attempt to exploit a vulnerability or brute-force credentials to gain access.

Breakpoint: The action of blocking the IP address interrupted the attack at the Delivery or Exploitation stages, preventing potential system compromise.

Tools & Technologies Used:

SIEM system for alert ingestion and analysis.

Threat Intelligence Platform (IP scanner) for threat verification.

Firewall for implementing containment measures.

Cyber Kill Chain model for tactical attack analysis.

Conclusion:
This project effectively demonstrates key competencies for an aspiring SOC analyst: data analysis skills, operational response capabilities, understanding of escalation processes, and the application of theoretical frameworks to incident analysis. It showcases readiness for a role in cybersecurity threat monitoring and response.


Projeto: Simulação do Fluxo de Trabalho de um Analista de SOC: Da Detecção à Escalação de Incidente
Descrição:
Este projeto apresenta uma análise detalhada de um cenário de plataforma de treinamento que simula as tarefas de um analista júnior de SOC (Security Operations Center). Ele abrange todo o ciclo de resposta a incidentes: análise de alertas em SIEM, verificação de ameaças, contenção e escalação adequada. Atenção especial é dada ao mapeamento de ações práticas para os estágios do modelo Cyber Kill Chain, demonstrando uma compreensão profunda dos processos de ataque e defesa.

Principais Etapas e Habilidades Demonstradas:

1. Detecção e Análise
Análise de Logs no SIEM: Alertas foram analisados para identificar atividade suspeita: múltiplas tentativas de conexão não autorizadas e autenticações SSH bem-sucedidas (porta 22) a partir do endereço IP 221.181.185.159.

Verificação de Ameaça: O IP foi verificado usando uma ferramenta interna de Threat Intelligence (ip-scanner.thm), que confirmou com 100% de confiança que era malicioso. Informações foram coletadas sobre seu ISP (China Mobile), geolocalização (Zhenjiang, China) e nome de domínio associado (chinamobileltd.thm).

2. Contenção e Erradicação
Resposta Imediata: O IP malicioso foi prontamente adicionado à lista de bloqueio do firewall (firewall.internal) para evitar tentativas adicionais de comunicação e conter a ameaça no perímetro da rede.

3. Escalação do Incidente
Tomada de Decisão: Após a resposta inicial, o membro adequado da equipe para escalação foi selecionado. Com base na análise de funções:

Will Griffin (Líder da Equipe SOC) foi escolhido como o ponto correto de escalação, pois é o supervisor direto dos analistas de SOC e coordena as ações de investigação adicionais, alinhando-se com os procedimentos operacionais padrão (SOP).

4. Contexto Teórico: Análise via Cyber Kill Chain
Decomposição do Ataque: As ações do atacante foram analisadas de acordo com o modelo Cyber Kill Chain:

Reconnaissance (Reconhecimento): O atacante provavelmente conduziu um reconhecimento preliminar para selecionar um alvo.

Weaponization (Armamentização): Preparação de payloads maliciosos ou scripts.

Delivery (Entrega): Tentativa de entregar o payload via ataque SSH.

Exploitation (Exploração): Tentativa de explorar uma vulnerabilidade ou forçar credenciais para obter acesso.

Ponto de Interrupção: A ação de bloquear o endereço IP interrompeu o ataque nos estágios de Delivery ou Exploitation, prevenindo um potencial comprometimento do sistema.

Ferramentas e Tecnologias Utilizadas:

Sistema SIEM para ingestão e análise de alertas.

Plataforma de Threat Intelligence (scanner de IP) para verificação de ameaças.

Firewall para implementação de medidas de contenção.

Modelo Cyber Kill Chain para análise tática de ataques.

Conclusão:
Este projeto demonstra com eficácia competências essenciais para um aspirante a analista de SOC: habilidades de análise de dados, capacidades de resposta operacional, compreensão dos processos de escalação e aplicação de frameworks teóricos para análise de incidentes. Mostra prontidão para atuar em funções de monitoramento e resposta a ameaças cibernéticas.


