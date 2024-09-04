### Desafio

- **Sistema:** Um sistema web que oferece funcionalidades como gestão de cursos, matrículas, notas, e calendário acadêmico.
- **Usuários Atuais:** 200 alunos.
- **Tecnologia:**
    - **Backend:** Aplicação monolítica em Java, utilizando Spring Boot.
    - **Frontend:** Aplicação web em Angular.
    - **Banco de Dados:** PostgreSQL, hospedado em um único servidor.
    - **Infraestrutura:** Hospedada em um servidor on-premises com recursos limitados (4 CPU, 16 GB RAM).
    - **Cenário de Uso:** Cerca de 20-30 requisições por minuto, especialmente nos horários de pico.

---

### Expansão

- **Expansão de Alunos:** Um aumento de 30.000 novos alunos além dos 200 já existentes.
- **Requisitos de Escalabilidade:**
    - O sistema deverá suportar até 5.000 usuários simultâneos nos horários de pico.
    - Latência máxima aceitável de 200 ms por requisição.
    - Alta disponibilidade com um SLA de 99,9%.
    - Capacidade de armazenar grandes volumes de dados acadêmicos (documentos, provas, etc.) e suporte a uploads de até 100 MB.
