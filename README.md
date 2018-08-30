# Contratação Freelancer
Este repósitório contem os desafios que o candidato a contratação deve realizar
## Instruções
1. Faça um fork desse repositório
2. Implemente o descrito nos Itens Back-end e Front-end (não serão aceitos candidatos que fizerem apenas um dos items)
3. Faça um Pull request para esse repositório (com nome e sobrenome)
## Desafios
### Front-end
1. Replique o layout dentro da pasta Materiais > Layout.png
2. Você deve deixá-lo responsivo utilizando o Framework Bootstrap
3. Crie os efeitos e animações que desejar para que deixe a navegação mais amigável e com uma usabilidade legal
4. Todo o site deve estar otimizado para SEO, utilizando as tags adequadas
5. Escolha um site e proponha melhorias (descritivo e o que vc faria para melhorar, não precisa ser implementado, pode ser enviado como um arquivo de texto dentro do repositorio (word, pdf, txt, etc...).
### Back-End
#### Contextualização
A loja de cosméticos ACME está lançando seu e-commerce, seus produtos são divididos nas categorias:
* Perfumes
* Sabonetes
* Hidratantes
* Máscaras
* Esfoliantes

Cada categoria pode ter vários produtos distintos.

#### Fazer
1. Você deve criar o banco de dados, inserir as categorias e três produtos de cada categoria de forma automatizada ultilizando factories e seeds
2. Criar um CRUD para categorias e produtos
  1. Nesse crud deve haver uma opção de busca por codigo ou nome (no mesmo campo) que deve fazer a busca por ajax e trazer o resultado
  2. A cada cadastro, alteração ou exclusão deve ser gerado um log
  3. Apagar lógicamente os dados (Soft Deletes)
3. Utilizar a API dos correios para cálculo de frete entre dois ceps (O usuário deve informar os dois ceps)
  1. Ao digitar o CEP deve ser feito uma busca do endereço completo (rua, bairro, cidade, estado) de acordo com o CEP informado
4. Criar uma API (Webservice) que receba: o tipo de retorno, o código **ou** nome do produto. Deve retornar o produto, incluindo o nome da categoria, em JSON ou XML, de acordo com o tipo de retorno escolhido)
5. Criar testes automatizados para testar o software (recomendado mas não obrigatório)
6. Todo o código deve estar comentado em **INGLÊS**
7. Deve ser seguido os padrões de codificação PSR-2
8. Todos os comentários de classe/função devem seguir a sintaxe "DocBlock"
## Será avaliado
### Front-end
* Conhecimento de HTML 5 e CSS 3
* Conhecimento do framework Bootstrap
* Noções de Javascript/Jquery (básico)
* Noções de UX/UI
* Noções de SEO
### Back-end
* Interpretação de texto
* Conhecimento do framework Laravel
* Criação de migrations e seeds
* Criação de CRUDS
* Relacionamentos utilizando Eloquent (OneToMany e ManyToOne)
* Noções de Javascript/Jquery (básico)
* Conhecimento sobre AJAX
* Busca e Resolução de Problemas
* Habilidade para utilizar API de terceiros
* Conhecimento sobre API Resftul
* Testes Automatizados de Software
* Inglês (Básico/Técnico)
* Padrões de Codificação PSR-2
* Documentação de Código
## Considerações para o teste
* Deve ser utilizado o framework Laravel 5.5
* Deve ser utilizado o framewok Bootstrap (versão 3 ou 4)
* É permitido utilizar qualquer pacote que te auxilie além dos recomendados
* Todos os desafios devem ser realizados dentro de 6 horas
  * Para contabilizar o tempo, é necessário criar um commit no momento de inicio do projeto, e outro commit ao final
  * Os candidatos que não fizerem o commit de inicio e fim de projeto, estarão automaticamente desclassificados
  * O Desafio deve ser entregue até no máximo 08:00 de 03/09/2018, os Pull request após esse horario serão eliminados
* Todo o material de apoio está dentro da pasta Materiais
## Pacotes Recomendados
* https://github.com/andersao/l5-repository
* https://github.com/spatie/laravel-activitylog
* https://github.com/kristijanhusak/laravel-form-builder
