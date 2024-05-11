## <img height="20" src="https://raw.githubusercontent.com/innng/innng/master/assets/soulgem-sayaka.gif"/> **Seja bem-vindo ao aplicativo de dicas de turismo para Airbnb! <img height="20" src="https://seeklogo.com/images/A/airbnb-logo-1D03C48906-seeklogo.com.png">** <img height="20" src="https://raw.githubusercontent.com/innng/innng/master/assets/soulgem-sayaka.gif"/>

<img height="20" width="100%" src="https://github.com/joaopauloaramuni/joaopauloaramuni/blob/main/img/footer-gray.gif?raw=true" />

**<img height="20" src="https://w7.pngwing.com/pngs/892/215/png-transparent-computer-icons-introduction-icon-cdr-angle-white.png"/> Introdução:**

Este aplicativo utiliza a tecnologia Gemini e Python para gerar dicas de turismo personalizadas para os hóspedes do Airbnb, com base em suas respostas a um conjunto de perguntas. O objetivo é oferecer uma experiência mais rica e memorável para os viajantes, ajudando-os a descobrir lugares interessantes e atividades que combinem com seus interesses.

**<img height="20" src="https://w7.pngwing.com/pngs/139/224/png-transparent-computer-icons-scalable-graphics-adobe-illustrator-artwork-apple-icon-format-functionality-icon-cdr-eps-svg-thumbnail.png"/> Funcionalidades:**

* **Configuração de localidade:** O aplicativo permite que o usuário defina o estado, cidade e bairro da sua hospedagem no Airbnb.
* **Configuração de preferências:** O usuário pode selecionar as categorias de lazer que mais lhe interessam, como Cultura, Esportes, Aventura, Gastronômico, sol e praia, Ecológico e Religioso.
* **Geração de dicas e roteiros:** Com base nas informações coletadas, o aplicativo gera dicas e roteiros personalizados para o hóspede, incluindo sugestões de lugares para visitar, restaurantes, eventos e atividades.
* **Interface amigável:** O aplicativo possui uma interface amigável e intuitiva, fácil de usar por pessoas de todos os níveis de conhecimento técnico.

**<img height="20" src="https://cdn-icons-png.flaticon.com/512/69/69211.png"/> Requisitos:**

* Python 3.6 ou superior <code><a href="https://www.python.org/" target="_blank"><img width="32" height="32" src="https://github.com/joaopauloaramuni/joaopauloaramuni/raw/main/img/python.png?raw=true"/></a></code>
* Google Colab ou ambiente local com Python e Google API Key configurados
* Biblioteca `google-generativeai` instalada

**<img height="20" src="https://w7.pngwing.com/pngs/878/325/png-transparent-instalator-computer-software-computer-icons-installation-others-angle-logo-computer-program.png"/> Instalação:**

1. Clone este repositório:

```bash
git clone git@github.com:ConanGoodwin/AIRBNB_Chat_bot.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute o aplicativo:

```bash
python app.py
```

**<img height="20" src="https://banner2.cleanpng.com/20180131/fee/kisspng-logo-brand-red-font-play-button-png-free-download-5a7245a9823028.9638690515174383775333.jpg"/> Uso:**

1. Siga as instruções na tela para configurar as informações da sua hospedagem e suas preferências de lazer.
2. O aplicativo irá gerar dicas e roteiros personalizados para você.
3. Explore as sugestões e personalize o seu roteiro de acordo com seus interesses e tempo disponível.

**<img height="20" src="https://e7.pngegg.com/pngimages/613/126/png-clipart-three-circle-and-two-line-logo-computer-icons-share-icon-sharing-symbol-share-miscellaneous-black-and-white.png"/> Contribuindo:**

Você é bem-vindo para contribuir com o desenvolvimento deste projeto! Se você tiver alguma ideia ou sugestão, por favor, envie um issue ou faça um pull request.

---
**Pontos de melhoria:**

* Deixar a parte de definição da localidade para um usuario administrador em separado, deixando o chat bot exclusivo para cada anfitrião do Airbnb, tirando do usuario a nescessidade de preencher a localidade cada vez que usar o mesmo.

* Usar a propria IA para na hora do prompt livre sobre os topicos, analisar se a pergunta esta dentro do contexto proposto pelo aplicativo, avisando o usuario quando fugir deste escopo para o mesmo decidir se prossegue por este caminho, ou até mesmo implementando maneiras de restringir esta possibilidade de fugir do escopo.

* Filtros avançados: oferecer filtros avançados para permitir que os usuários refinem as sugestões de acordo com suas preferências específicas, como faixa etária, orçamento, e acessibilidade.

**Links Úteis:**

* [Repositório do projeto](https://github.com/ConanGoodwin/AIRBNB_Chat_bot/tree/main)
* [Documentação da API Gemini](https://docs.gemini.com/)
* [Comunidade Python](https://www.python.org/community/)

**Esperamos que este aplicativo seja útil para você e que ele ajude a tornar a sua experiência no Airbnb ainda mais especial!**
