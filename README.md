# AZ900-dio
Repositório para estudo do exame AZ900 

### Computação em nuvem – fornecimento de serviços de computação pela internet (rápido, flexível e escalável). Há três modelos de nuvem:
- Privada – ambiente para uma única empresa, fornecendo acesso apenas para usuários da organização. 
- Pública – ambiente para diferentes clientes, como a Microsoft. Os clientes podem acessar pagando, usando uma rede segura (internet).
- Híbrida – Há recursos do ambiente privado e público, eles podem se comunicar. Isso permite que os aplicativos sejam executados no local mais adequado.

### Comparação de modelos de nuvem
- Pública – sem despesas para escalar verticalmente (pago pelo serviço), aplicativos podem ser provisionados (preparados) e retirados rapidamente e as organizações pagam apenas pelo que utilizam.
- Privada – A organização tem controle sobre recursos (servidores, computadores, conexões...) e segurança. Responsável pela manutenção e atualização do hardware (para escalar, preciso melhor o hardware...).
- Híbrido – A organização escolhe onde executar seus aplicativos (público ou privado), há um controle da segurança, conformidade e requisitos legais (conforme as exigências da empresa) e há maior flexibilidade (criar os recursos dependendo da região/local). Dados ultra sensíveis podem ser armazenados em nuvem privada, enquanto que demais dados e aplicações podem ser trabalhados em nuvem pública.
  
### CapEx – despesas de capital
- Gasto inicial de dinheiro em infraestrutura física (comprar equipamentos, energia elétrica, espaço físico, servidores, refrigeração...).
- Despesas do CapEx têm um valor que se reduz com o tempo. Após o investimento inicial na infraestrutura, os custos serão apenas para manter ela (bem menor em relação a valor investido para comprar os equipamentos).

### OpEx – despesas operacionais
- Gasto com produtos e serviços conforme necessários, pagamento conforme o uso. Há uma cobrança contínua, conforme utilizo os recursos de nuvem.
- Cobrado imediatamente pelo consumo (modelo baseado em consumo).
- Melhor previsão de custos, preço para recursos e serviços individuais.

## Benefícios da Computação em Nuvem
1.	Alta disponibilidade se concentra em garante a disponibilidade máximo, independentemente de interrupções ou eventos que possam ocorrer.
a.	Recursos disponíveis sempre que necessário
b.	Serviços entregáveis
c.	Azure SLA – avalia a quantidade de tempo (baseado em modelos de %, como 99%, 99.9%...) que aquele serviço fica indisponível no ano. Isso está dentro do acordo de nível de serviço, se ultrapassar esse tempo de indisponibilidade, a Microsoft ressarce o usuário.

2.	Escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda, assim podendo adicionar mais recursos conforme as requisições.
a.	Paga apenas pelos serviços (não preciso pagar para comprar um novo servidor, por exemplo)
b.	Caso a demanda caia, posso reduzir os recursos, reduzindo custos.
c.	Escalando vertical, posso adicionar mais CPUs e RAM à máquina virtual.

3.	Elasticidade, caso haja um salto repentino na demanda, os recursos implantados podem ser expandidos (manual ou automático).
a.	Alta demanda em sites de compra na black Friday
b.	Pode ser adicionado máquinas virtuais ou contêineres por meio de expansão
c.	Se houver quase na demanda, os recursos implantados poderão ser reduzidos horizontalmente. 

4.	Confiabilidade, devido ao design descentralizado, a nuvem naturalmente suporta uma infraestrutura confiável e resiliente.
a.	Ser descentralizado permite que o usuário tenha recursos implantado em várias regiões do mundo.
b.	Devido a escala global, caso haja um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. 

5.	Previsibilidade, remete a confiança no desempenho das aplicações ou nos custos. Ambas são influenciadas pelo Microsoft Azure well-architected framework.

6.	Segurança, a nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes, mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente (não é obrigação da Microsoft).

7.	Governança, como vamos gerir os recursos e padrões. 
a.	Auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação (resolução de problemas).
b.	Posso escolher que recursos não estejam disponíveis para uma determinada região.

8.	Gerenciabilidade, permite gerenciar a nuvem usando diferentes recursos (IDEs), facilita o gerenciamento pelos usuários usando o portal, chamadas de API, power shell, Visual Studio...
a.	Escalar automaticamente a implantação de recursos com base na necessidade. 
b.	Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
c.	Maneira como gerenciamos o ambiente de nuvem e seus recursos, usando: portal da web, interface de linhas de comando, usando APIs, power shell.

## SLA – Service Level Agreement
Nos diz respeito sobre o tempo de inatividade por período, conforme o acordo. Assim, é aceitável que o serviço fiquei indisponível por um determinado período de tempo, conforme a SLA. Quando maior o SLA (%) menor será o tempo de inatividade, sempre olhar para a quantidade de ‘9’.
<img width="886" height="183" alt="image" src="https://github.com/user-attachments/assets/e8905f1f-f2cf-4076-a1f9-714dbcc194c1" />

 

