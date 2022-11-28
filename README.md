# TF-Selenium
Repositório dedicado a estudos de testes funcionais com a ferramenta Selenium

**README EM CONSTRUÇÃO**
<p align="center">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQiLfTTKRApG4kd5iCzmazTJARxHiwu8DLJEjLCBRniiPedkdKzEdJwufin84_9Lp4-u0I&usqp=CAU"/>
</p>


1. *O que é o Selenium*

O Selenium é um conjunto de Ferramentas de código aberto usado para testar aplicações web de forma automatizada. Ele executa testes entre navegadores e plataformas     diferentes para simular a interação de um usuário e garantir o funcionamento do software.
 
  
 2. *Ferramentas disponíveis*
 
 * WebDriver
 * IDE
 * GRID
 
 
 [Fonte](https://tecnoblog.net/responde/o-que-e-selenium-em-programacao/)
 
 
 **Exemplo de código em Java utilizando o Selenium WebDriver para o navegador Firefox e JUnit**
 

     @Test
    public void testTextField() {
     System.setProperty("webdriver.gecko.driver", System.getProperty("user.dir") + "/geckodriver.exe");
     
     WebDriver webDriver = new FirefoxDriver();
     webDriver.manage().window().maximize();
     webDriver.get("http://www.google.com");

     Assert.assertEquals("Google", webDriver.getTitle());

     webDriver.quit();

    }
 
 
 [Clique aqui para acessar página de download das Ferramentas](https://www.selenium.dev/)
