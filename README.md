[![author](https://img.shields.io/badge/author-brunonascimento-red.svg)](https://www.linkedin.com/in/brunoanascimento/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/BrunoAqNascimento/Analytics-and-Data-Science-Projects/issues)


<p align="center">
  <img src="https://image.freepik.com/free-photo/beautiful-panoramic-shot-new-york-city_181624-433.jpg" alt="imagem maneira relacionada ao projeto"height=400px >
</p>

# EDA | Airbnb | New York

[Airbnb](https://www.airbnb.com.br/) is one of the main examples of businesses modeled on the concept of shared economy, that is, they don't own what they offer. Airbnb can be considered as a **hotel company**, however it **doesn't have any hotels or residences that it rents**!

It's basically an accommodation rental platform that allows hosts can rent their private properties for guests that need somewhere to stay.

Connecting people who want to travel (and stay) with hosts who want to conveniently rent their properties and earn income by offering this accommodation service, Airbnb provides an innovative platform to make this accommodation alternative.

The company started in 2007, when roommates Brian Chesky and Joe Gebbia started “AirBed & Breakfast” in their living room. They started by providing air mattresses and breakfast, as the name implies, for guests who couldn't find alternative accommodation in town.

The company began its global expansion in 2021, opening its first international office in Hamburg, Germany. Today, it already offers more than 6 million third-party accommodations in more than 100,000 cities in 191 countries.

At the end of 2018, the Startup, founded 11 years ago, had already **offered accommodation to more than 300 million** people around the world, clashing with traditional hotel chains.

<center><img alt="Analyzing Airbnb" width="10%" src="https://www.area360.com.au/wp-content/uploads/2017/09/airbnb-logo.jpg">< /center>
  
New York is among the three cities worldwide with the highest number of apartments and accommodations listed on its marketplace platform. The company's business in the city is a fascinating look at how the sharing economy has evolved, as well as the challenges they will still face.
  
 <img src="https://image.freepik.com/free-photo/beautiful-panoramic-shot-new-york-city_181624-433.jpg" alt="project-related way image"height=400px >
</p>

New York City is the most populous city in the United States. New York is one of the most populous megacities in the world. New York City has been described as the cultural, financial and media capital of the world, significantly influencing commerce, entertainment, research, technology, education, politics, tourism, restaurants, art, fashion and sports, and is the most photographed city in the world. In addition to the planet's financial capital, it is also at the forefront when it comes to technology and innovation. Its ecosystem has attracted the attention of the whole world, creating a favorable environment for the creation of technology and internet companies, becoming one of the largest innovation hubs in the world.
  
Therefore, I believe that a prior descriptive analysis of prices and options for renting accommodation (rooms and apartments) on Airbnb may be useful to guide the tourist who plans to visit NY in the future.

One of Airbnb's initiatives is to make website data available for some of the world's major cities to provide data that quantifies the impact of short-term rentals on residential and housing communities, and also provides a platform to support advocacy. policies to protect cities from the impacts of short-term rentals. The [Inside Airbnb] portal (http://insideairbnb.com/get-the-data.html), provides data compiled from the Airbnb website for listings available for New York City, making it possible to download a large amount of data in order to to develop *Data Science* projects that can deliver solutions for the ecosystem.

In this project, we will do an exploratory data analysis (EDA) on New York City data on accommodations offered on the platform and rental prices charged, and see what insights can be extracted from the raw data.  

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

O [Airbnb](https://www.airbnb.com.br/) é um dos principais exemplos de negócios modelados com o conceito de economia compartilhada, ou seja, não são proprietárias daquilo que oferecem. O Airbnb pode ser considerado como uma **empresa hoteleira**, contudo **não possui nenhum hotel ou residência que aluga**!

É basicamente um marketplace de aluguel de acomodações que permite que anfitriões aluguem suas propriedades privadas para hóspedes que precisam de algum lugar para ficar. Intermediando uma negociação entre o anfitrião e o hóspede.

Conectando pessoas que querem viajar (e se hospedar) com anfitriões que querem alugar seus imóveis de maneira prática e obter renda oferecendo esse serviço de acomodação, o Airbnb fornece uma plataforma inovadora para tornar essa hospedagem alternativa.

A companhia teve início em 2007, quando os colegas de quarto Brian Chesky e Joe Gebbia começaram o “AirBed & Breakfast” em sua sala de estar. Os amigos forneceram colchões de ar e café da manhã, como o nome sinaliza, para hóspedes que não conseguiam encontrar uma acomodação alternativa na cidade.

A companhia começou sua expansão global em 2021, abrindo seu primeiro escritório internacional em Hamburgo, na Alemanha. Hoje em dia, ela já oferece mais de 6 milhões de acomodações de terceiros em mais de 100 mil cidades de 191 países.

No final de 2018, a Startup fundada 11 anos atrás, já havia **oferecido hospedagem a mais de 300 milhões** de pessoas ao redor de todo o mundo, batendo de frente com as redes hoteleiras tradicionais.

<center><img alt="Analisando Airbnb" width="10%" src="https://www.area360.com.au/wp-content/uploads/2017/09/airbnb-logo.jpg"></center>

Nova York está entre as três cidades  a nível mundial com o maior número de apartamentos e acomodações listadas na sua plataforma de marketplace. Os negócios da companhia na cidade são uma visão fascinante de como a economia compartilhada evoluiu, bem como os desafios que ainda estão por vir.

<p align="center">
  <img src="https://image.freepik.com/free-photo/beautiful-panoramic-shot-new-york-city_181624-433.jpg" alt="imagem maneira relacionada ao projeto"height=400px >
</p>

A cidade de Nova York é a cidade mais populosa dos Estados Unidos. Nova York é uma das megalópoles mais populosas do mundo. A cidade de Nova York foi descrita como a capital cultural, financeira e da mídia do mundo, influenciando significativamente o comércio, entretenimento, pesquisa, tecnologia, educação, política, turismo, restaurantes, arte, moda e esportes, e é a cidade mais fotografada no mundo. Além de capital financeira do planeta, também está na linha de frente quando o assunto é tecnologia e inovação. Seu ecossistema tem chamado a atenção do mundo inteiro, criando um ambiente favorável à criação de empresas de tecnologia e internet, se tornando um dos maiores hubs de inovação do mundo.

Um componente vital da economia da cidade de Nova York, sem dúvidas, é a indústria do turismo, sustentando mais de 376.800 empregos (representando quase 10 por cento de todos os empregos do setor privado). A indústria funciona como um ecossistema dinâmico que oferece experiências incriveis de entreterimento, alimentação e negócios.[Fonte](https://www.osc.state.ny.us/reports/osdc/tourism-industry-new-york-city)

Portanto, acredito que uma análise descritiva prévia sobre os preços e opções de locação de acomodações(quartos e apartamentos) no Airbnb, possa vir a ser útil para nortear o turista que planeja visitar NY futuramente.

Uma das iniciativas do Airbnb é disponibilizar dados do site, para algumas das principais cidades do mundo, com intuito de fornecer dados que quantificam o impacto dos aluguéis de curto prazo em comunidades residenciais e de habitação, e também fornece uma plataforma para apoiar a defesa de políticas para proteger as cidades dos impactos de aluguéis de curto prazo. O portal [Inside Airbnb](http://insideairbnb.com/get-the-data.html), fornece dados compilados do site do Airbnb para anúncios disponíveis para a cidade de Nova York, possibilitando baixar uma grande quantidade de dados com intuito de desenvolver projetos de *Data Science* que possam entregar soluções para o ecossistema.

Neste projeto, faremos uma análise exploratória de dados (EDA) sobre os dados da cidade de Nova York sobre as acomodações oferecidas na plataforma e os preços de aluguel praticados, e visualizar quais insights podem ser extraídos dos dados brutos.


