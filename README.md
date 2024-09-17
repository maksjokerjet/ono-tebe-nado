<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Оно тебе надо — аукцион вещей, в которые никто не верил</title>
    <link rel="stylesheet" href="fonts/fonts.css">
    <link rel="stylesheet" href="styles/global.css">
    <link rel="stylesheet" href="styles/style.css">
  </head>
  <body>
    <header class="header">
      <ul class="header__links-list">
        <li class="header__links-list-item header__links-list-item_no-bullit">
          <a class="header__link header__link_active" href="#0">главная</a>
        </li>
        <li class="header__links-list-item">
          <a class="header__link" href="#0">посмотреть лоты</a>
        </li>
        <li class="header__links-list-item">
          <a class="header__link" href="#0">об аукционе</a>
        </li>
      </ul>
      <div class="header__logo">
        <a class="link_logo">
          <img
            class="header__logo-image"
            src="images/logo-black.svg"
            alt="Логотип">
        </a>
      </div>
      <address class="adress">
        <ul class="header__address">
          <li>
            <a href="tel:+9_999_555_5555">+9 999 555 5555</a>
          </li>
          <li>
            <a href="info@sobaka.ge">info@sobaka.ge</a>
          </li>
          <li>
            <span>наб. Принсенграхт 263- <br>265, Амстердам</span>
          </li>
        </ul>
      </address>
    </header>
    <main class="cover">
      <h1 class="cover_title">
        <span class="cover__title_word-spacing font_cover"><span class="cover__title_letter-spacing">он</span>
          <span>о</span></span>
        <span class="cover__title_word-spacing aligned-text_center font_cover"><span class="cover__title_letter-spacing">теб</span>
          <span>е</span></span>
        <span
          class="cover__title_word-spacing_plus aligned-text_right font_cover"><span>н</span> <span class="cover__title_letter-spacing">ад</span><span>о</span></span>
      </h1>
      <div class="cover__description">
        <h2 class="cover__description-text">
          <span>Аукцион вещей, </span>
          <span>в </span>
          <span class="cover__description-text-special_spacing"
            >которые никто не верил</span>
        </h2>
        <div class="button">
          <button class="bet-button">
            <span>Сделать ставку</span>
          </button>
        </div>
      </div>
      <div class="overlay"></div>
      <!-- Если Overlay сделать в конце секции и дать ему position absolute, а к секции с position reletive, то получим затемнение-->
    </main>
    <section class="lots">
      <h2 class="lots__heading">Лоты</h2>
      <div class="lots__card-list">
        <a class="none-decoration" href="#0">
          <div class="cards card_type_film">
            <h3 class="card__title">
              Фильм режиссёра, который бросил киношколу
            </h3>
            <h4 class="card__text">
              <p>
              <span
                >Не просто бросил, а ушёл с первой лекции. Какой была бы ваша
                ставка, если бы вы не знали, что режиссёр — Пол Томас
                Андерсон?</span>
              </p>
            </h4>
            <div class="overlay"></div>
          </div>
        </a>
        <a class="none-decoration" href="#0">
          <div class="cards card_type_book">
            <h3 class="card__title">
              Книга, где описан один скучный день из жизни рекламного агента
            </h3>
            <h4 class="card__text">
              <p>
                Объёмом почти в тысячу страниц. Иногда без знаков препинания и с
                переходами на древнеанглийский. В ней одновременно рассказывается
                о 16 июня 1904 года и об истории литературы, начиная с античных
                времён. И это всё накладывается на эпическую поэму Гомера. Сколько
                бы вы поставили на «Улисса» Джеймса Джойса?
              </p>
            </h4>
            <div class="overlay"></div>
          </div>
        </a>
        <a class="none-decoration" href="#0">
          <div class="cards card_type_picture">
            <h3 class="card__title">
              Картина, которую повторит даже 5-летний сын маминой подруги
            </h3>
            <h4 class="card__text">
              <p>
                Ну действительно, там линия, тут кружочек, а здесь и вовсе что-то
                похожее на инфузорию-туфельку. Никаких полей, лесов, котиков...
                Сколько бы вы на такое поставили, если бы не знали, что это — одна
                из революционных работ Кандинского?
              </p>
            </h4>
            <div class="overlay"></div>
          </div>
        </a>
      </div>
      <p class="lots__look-more-link"><a>посмотреть больше</a></p>
    </section>
    <section class="about">
      <div class="about__logo">
        <a>
          <img
            class="about__logo-image"
            src=".//images/logo-white.svg"
            alt="Логотип">
        </a>
      </div>
      <div class="about_text">
        <h2 class="about__title">Об аукционе</h2>
        <h4 class="about__text">
          <p>
            Здесь вы не встретите очередное пафосное собрание невероятно дорогого
            антиквариата. Наши лоты вообще не должны были попасть ни на один
            аукцион. Потому что кому нужен дневник девочки-подростка или картина,
            которую может нарисовать даже ребёнок? Кому нужны все эти странные
            вещи, созданные любителями?
          </p>
        </h4>
        <h4 class="about__text indent">
          <p>
            Слишком сложные или, наоборот, слишком простые. Опережающие своё
            время. В пух и прах растерзанные критиками. Непринятые и непонятые.
            Когда-то они казались просто неудачными. Но, несмотря на критику,
            кажущуюся простоту или сложность, сейчас без этих лотов невозможно
            представить современную культуру. Когда в эти вещи не верил никто,
            продолжали верить их создатели. И сейчас эти лоты стали культовыми.
          </p>
        </h4>
      </div>
    </section>
    <footer class="footer">
      <address class="adress_footer">
        <ul class="adress_footer_list">
          <li class="adress_footer_list_item">
            <a class="adress_footer_number" href="tel:+9_999_555_5555"
              >+9 999 555 5555</a
            >
          </li>
          <li class="ul_footer">
            <a class="adress_footer_mail" href="info@sobaka.ge"
              >info@sobaka.ge</a
            >
          </li>
          <li class="ul_footer">
            <span class="adress_footer_adress"
              >наб. Принсенграхт 263- 265, Амстердам</span
            >
          </li>
        </ul>
      </address>
      <nav class="footer__menu">
        <ul class="footer__menu-list">
          <li class="footer__menu-list-item">
            <a class="footer__menu-link_active" href="#0">главная</a>
          </li>
          <li class="footer__menu-list-item">
            <a href="#0">посмотреть лоты</a>
          </li>
          <li class="footer__menu-list-item"><a href="#0">об аукционе</a></li>
        </ul>
      </nav>
      <div class="footer__social-list">
        <a class="footer__social-link">
          <img class="footer__social-icon" src="images/yt.svg" alt="Youtube">
        </a>
        <a class="footer__social-link">
          <img
            class="footer__social-icon"
            src="images/vk.svg"
            alt="Vkontakte">
        </a>
        <a class="footer__social-link">
          <img
            class="footer__social-icon"
            src="images/pinterest.svg"
            alt="Pinterest">
        </a>
      </div>
    </footer>
  </body>
</html>
