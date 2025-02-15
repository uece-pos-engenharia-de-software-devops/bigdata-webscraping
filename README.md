# Web Scraping de Notícias da UECE

## Autores
- Marcos Eduardo da Silva Santos  
- Ezemir Sabino Cavalcante  

## Sobre o Projeto

O código realiza a extração de notícias do site da UECE utilizando Selenium para navegação e BeautifulSoup para parsing do HTML. O objetivo é coletar até 50 notícias, armazenando os títulos e descrições em um arquivo JSON.

## Tecnologias Utilizadas  

- **Python 3**: Linguagem de programação de alto nível, orientada a objetos e de código aberto, licenciada sob a **PSF License**. Utilizada para executar o web scraping e manipular os dados extraídos. 🔗 [Site Oficial](https://www.python.org/)  

- **Selenium**: Biblioteca para automação de navegadores, permitindo interação dinâmica com páginas da web, distribuída sob a **Apache License 2.0**. Usada para carregar a página de notícias e clicar no botão "Veja Mais". 🔗 [Site Oficial](https://www.selenium.dev/)  

- **BeautifulSoup4**: Biblioteca para parsing de HTML e XML, facilitando a extração de dados estruturados, licenciada sob a **MIT License**. Utilizada para analisar o HTML carregado pelo Selenium e extrair títulos e descrições das notícias. 🔗 [Site Oficial](https://www.crummy.com/software/BeautifulSoup/)  

- **Pandas**: Biblioteca para manipulação e análise de dados, amplamente usada em ciência de dados e automação, licenciada sob a **BSD 3-Clause License**. Responsável por organizar os dados extraídos em um DataFrame e convertê-los para JSON. 🔗 [Site Oficial](https://pandas.pydata.org/)

## Como Executar

### Clonar o Projeto
Para obter o código, clone o repositório:
```sh
git clone https://github.com/uece-pos-engenharia-de-software-devops/bigdata-webscraping.git
```
1. Instale as dependências:
   ```sh
   pip install selenium beautifulsoup4 pandas
   ```
2. Execute o script:
   ```sh
   python main.py
   ```
3. O resultado será salvo no arquivo `results.json`.

## Sobre o Curso
Este projeto foi desenvolvido na disciplina de **Big Data**, ministrada pelo professor **Denis Menezes de Sousa**, como parte da **Especialização em Engenharia de Software com DevOps**.

## Demo
![Demo](demo.gif)

