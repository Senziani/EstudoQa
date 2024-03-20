# Estrategias e tipos de teste

* Como monstar uma estrutura de teste de teste para cada fase de desenvolvimento

                • Teste Unitario
                • Teste de integração
                • Teste de sistema


* **Teste unitario**

        • Criado pelo DEV;
        • pode ser feito pelo QA, porém tira a responsabilidade de clean code do dev;
        • Testar funcionadade especificas como somas em uma calculadora.

* **teste de integração**

        • Uns dos testes mais problematicos
        • Verificado por logs, respostas do sistemas.
    

* **Teste de sistema**

        • Validacão como se fosse usuario

                ○ Testar novas funcionalidades
                ○ Testar antigas funcionalidades

                    ► è normal novas funcionalidades afetarem as antigas

                             
* **Teste Funcionais**
                    

        • Valida a funcionalidade do sistema

        • Tipos de testes funcionais

                ○ Caixa Preta (Black Box) 

                    ► Sem acesso ao codigo fonte;
                    ► Você é o usuario;
                    ► Teste manuais como Criar, ler , atualizar , Deletar (CRUD).

                ○ Caixa Branca (White Box)

                    ► Tema acesso ao codigo;
                    ► Teste de condicionais e caminhos logicos;
                    ► Fluxo de dados.

                ○ Caixa Cinza (Gray Box)

                    ► Misto black e white box;
                    ► Verifica como uma informação no front end se comporta no back end

                        ▬ Requisição HTTP
                        ▬ Banco de dados

* **Teste nao Funcional**

        • Teste de performance , acessibilidade

            ○ Criticar protudo

                ► Validar performance , acessibilidade
                ► Confibabilidade do sistema
                ► Ferramentas metricas

* **Teste de manutenção**   

        • Teste de regressão 

                ○ Regressão é um teste usado quando a novas funcionalidades e temos que testar
                as antigas para saber se as novas funcionalidades na afetou a antiga

            

