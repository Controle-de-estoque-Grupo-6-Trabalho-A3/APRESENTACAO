<h1>Sistema de Gerenciamento de Estoque de Tintas</h1>

![estoque](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/5c59ac02-5c6b-4205-8731-175aff9d4e45)

<h2>Introdução</h2>

No cenário do varejo, a gestão eficiente do estoque é um elemento crucial para o sucesso de qualquer negócio. Em setores específicos, como o de lojas de tintas, onde a diversidade de produtos e a necessidade de um controle preciso são ainda mais evidentes, a implementação de um sistema de CRUD (Criar, Ler, Atualizar, Excluir) torna-se imperativa. Este sistema, ao permitir uma manipulação simples e eficaz dos dados do estoque, oferece não apenas organização, mas também uma base sólida para a tomada de decisões estratégicas.

<h2>Motivações</h2>

<ul>
  <li>Otimização operacional: A manipulação ágil de dados do estoque simplifica tarefas diárias, suavizando redundâncias e acelerando processos.</li>
  <li>Eficiência administrativa: Em setores com ampla variedade de produtos, como tintas, a eficiência administrativa é vital. O sistema de CRUD oferece uma plataforma que simplifica a adição, visualização, modificação e exclusão de dados, contribuindo para uma gestão mais eficiente.</li>
  <li>Tomada de decisões estratégicas: Capacitar gestores com dados atualizados possibilita a tomada de decisões estratégicas informadas. O sistema de CRUD torna-se uma ferramenta avançada para identificar oportunidades de crescimento e aprimorar a experiência do cliente.</li>
  <li>Prevenção de falta de estoque: A agilidade na reposição de produtos é essencial. O sistema auxilia na prevenção de falta de estoque, garantindo que a demanda seja atendida de maneira oportuna.</li>
</ul>

<h2>Desenvolvimento do projeto</h2>
<ul>
  <li>Linguagem de programação: PYTHON</li>
    ![pitao (2)](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/a75fdc90-90bc-490d-a3be-92ff2b5ffb92)
  <li>Programação orientada a objetos</li>
  <li>Principais classes:
    
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/ec7e5691-f9f7-4045-aee5-237092c886ec)
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/461ec994-99d5-4a28-a135-375e84c5f221)
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/2714e1fe-fcad-4357-9fe7-847a9c8fe830)
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/92f2071c-6c85-4539-a9e8-3038272fef8b)
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/d8f698d7-4f31-44f7-b184-73f6765dbc21)
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/32a1768d-722f-4bf5-9ee4-b7a3023eba87)

  </ul>
</li>

<h2>Desafios e Soluções</h2>
<ul>
  <li>
    <strong>Gestão de Transações e Estoque Atualizado:</strong>
    <br>Desafio: Garantir que as transações de compra e venda atualizem o estoque de maneira consistente.
    <br>Solução: Implementar um mecanismo robusto para garantir a atomicidade das transações, por exemplo, utilizando transações em banco de dados (usamos o SQLite).
  </li>
  <li>
    <strong>Segurança na Manipulação de Dados Sensíveis:</strong>
    <br>Desafio: Lidar com informações sensíveis, como dados dos clientes (CPF, endereço, etc.), de forma segura e protegida.
    <br>Solução: (Não implementamos, pode ser uma melhoria futura) Implementar práticas de segurança, como criptografia de dados protegidos, restrições de acesso baseadas em funções (RBAC) e validação rigorosa de entrada de dados para prevenir possíveis vulnerabilidades.
  </li>
</ul>

<h2>Fase de Testes</h2>
<ul>
  <li>
    <strong>Testes Unitários:</strong>
    <br>Utilizamos o framework pytest para realizarmos os testes do programa.
  </li>
</ul>

![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/32dd81ee-1ed9-444a-8b3b-42884dd11c12)
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/827bb0be-4ef1-4ef9-a977-5af4ddc9e179)
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/6fbec333-dc86-4cd2-9cf2-00c898b52061)

<h2>Resultado Positivo de Todos os Testes Unitários Realizados</h2> 
![image](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/8417e9ba-238f-4c83-9ad2-bf3783b8f6de)

<h2>Resultado dos Testes de Métricas e de Cobertura</h2>
![PRINT Métricas Crud](https://github.com/Controle-de-estoque-Grupo-6-Trabalho-A3/APRESENTACAO/assets/143462705/5087f64c-4333-4d5d-8913-d66ee5f39db3)

<h2>Exemplos de Uso com o Código em Funcionamento:</h2>
<!-- COLOCAR PRINT DO CÓDIGO RODANDO AQUI -->


# Conclusão
Em conclusão, este projeto não foi apenas comprovado em um sistema funcional para gerenciamento de estoque de tintas, mas também proporcionou uma experiência de aprendizado aprimorada. As lições aprendidas ao superar desafios e aprimorar habilidades técnicas são inestimáveis ​​para o desenvolvimento contínuo da equipe. Este sistema representa não apenas uma solução prática para a gestão de depósitos de tintas, mas também um marco em nossa jornada de crescimento e excelência no desenvolvimento de software.
