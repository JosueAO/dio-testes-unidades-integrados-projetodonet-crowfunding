## Versão 2 do REAMDME.md. Projeto(treinamento) Finalizado.

### Testando um projeto de crowdfunding (vaquinha online) desenvolvido em .Net Core com a arquitetura MVC aplicando os principais conceitos de testes para aumentar a qualidade de entrega dos projetos com testes de unidade, integrados e TDD.

### Este repositório possui um PDF com uma breve explanação sobre o tema testes unitário/unidade e integrados em .NET.

### Além do especialista Eliézar, Marcos Freire assessora na explanação e observações. 

### Ferramentas usadas:
 
 - Biblioteca Bogus para gerar dados fake válidos para testes;
 - Mock para siular comportamentos;
 - Xunit.net para testes unitátios/inidade;
 - Framework Selenium para testes automatizados(teste de interface, comportamento do usuário);
 - TDD (Test Driven Development).

 ### Opções de configurações e outras observações estão como comentários no código. Um exemplo abaixo, caso seja escolhido o navegador Chrome como braowser para teste usando o Selenium. No código, existe cofigurações para Firefox tambem.

#### /*ChromeOptions options = new ChromeOptions();
####            options.AddArgument("headless");
####            options.AddArgument("no-sandbox");
####            //options.AddArgument("proxy-server='direct://'");
####            options.AddArgument("proxy-auto-detect");
####            options.AddArgument("proxy-bypass-list=*");
####            options.AddUserProfilePreference("disable-popup-blocking", "true");
#### */
####            // Inicializa o IWebDriver do selenium, é ele que disponibiliza as consultas e manipulacoes das paginas. 
####            //_driver = new ChromeDriver(service, options);

------------------------------------------------------------------------------------
## Este repositório faz parte dos cursos/bootcamps da Digital Innovation One
