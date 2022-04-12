<template lang="pug">
    div

        header.header
            .container.header-container
                a(href="").logo
                div.header-contacts
                    a(href="").header__link.header__link--phone +7 (495) 123-45-56
                    a(href="").header__link.header__link--email support@wshost.ru
                div.header__right-part
                    button.header__button-buy Купить хостинг
                    a(href="").header__link--account

        .section-nav
            ul.container.nav__list
                li.nav__item
                    a(href="").nav__link ХОСТИНГ
                li.nav__item
                    a(href="").nav__link VPS
                li.nav__item
                    a(href="").nav__link  РЕГИСТРАЦИЯ ДОМЕНОВ
                li.nav__item
                    a(href="").nav__link SSL
                li.nav__item
                    a(href="").nav__link  ХОСТИНГ-ПРОВАЙДЕР


        .section-about
            .container.about-container
                h1.about__h1 Платный хостинг для сайта
                p.about__p.about__p--normal Совместим с любыми CMS:
                p.about__p.about__p--bold 1С-Битрикс, Wordpress, Opencart, DLE, Joomla и др.
                p.about__p.about__p--normal Всё включено:
                p.about__p.about__p--bold PHP 5.4 – 8.0, Perl, FTP, MySQL, ISPManager
                a(href="").orange-btn Заказать хостинг


        .section-rates
            .container
                h2.h2 Тарифы на хостинг
                p.rates__text У нас оптимальные тарифы на классический виртуальный хостинг с <span class="bold-text"> безлимитными </span> ресурсами на количество сайтов, баз данных и FTP.
                p.rates__text Выбирайте наш лучший безлимитный хостинг в России!
                ul.rates__type-list
                    li.rates__type-item
                        img(src="./assets/rates-1.svg")
                        p.rates__type-heading МИНИ
                p.rates__description Неограниченно сайтов, баз данных MySQL, FTP аккаунтов и почтовых ящиков
                ul.rates__option-list
                    li.rates__option-item
                        p.rates__memory 2Gb места SSD
                        p.rates__option PHP - 5.6, 7.0, 7.1, 7.2, 7.3, 7.4
                        p.rates__option Поддержка любой CMS
                        p.rates__option Бесплатные SSL сертификаты Let's Encrypt
                        p.rates__option Защита от DDoS
                        div.rates__price-wrapper
                            p.rates__price 99P
                            p.rates__price 99P
                            p.rates__price 99P
                            p.rates__price 99P
                        a(href="").rates__btn-buy-host Купить хостинг
                a(href="").rates__btn-all-options Посмотреть все характеристики нашего хостинга

        .section-advantages
            .container.advantages-container
                img(src="./assets/advantages.svg")
                div
                    h3.h3 Вместе с хостингом Вы получите
                        p.advantages__text 30 дней на тестовый период + 100% возврат денег, если хостинг не подойдёт
                        p.advantages__text Хостинг в подарок при оплате тарифа на 1 год
                        p.advantages__text Бесплатный перенос сайта от другого хостинг-провайдера

        .section-cms
            .container
                h2.h2.cms-h2 Хостинг с поддержкой любой CMS
                p.cms__content На нашем виртуальном хостинге вы сможете разместить сайт <span class="bold-text">на любой CMS</span>, а также установить в два клика любую популярную систему управлению сайтом
                div.cms__images-wrapper
                    img(src="./assets/1c.svg").cms__image
                    img(src="./assets/WordPress.svg").cms__image
                    img(src="./assets/Joomla.svg").cms__image
                    img(src="./assets/modx.svg").cms__image
                    img(src="./assets/opencard.svg").cms__image
                    img(src="./assets/umi-cms.svg").cms__image
                    img(src="./assets/drupal.svg").cms__image
                    img(src="./assets/instant.svg").cms__image
                    img(src="./assets/netcat.svg").cms__image
                    img(src="./assets/phpBB.svg").cms__image
                    img(src="./assets/shop.svg").cms__image
                    img(src="./assets/DLE.svg").cms__image
                    img(src="./assets/host.svg").cms__image
                    img(src="./assets/prestashop.svg").cms__image


        .section-certificates
            .container
                h2.h2 SSL-сертификаты
                p.certificates__description Купить SSL и попасть в TOP Google. WSHOST предлагает низкие цены и быстрый выпуск за счет <span class="bold-text">уникальных</span> партнерских условий с удостоверяющими центрами.
                p.certificates__description  Подберите сертификат исходя из задач и предпочтений, удобные фильтры и описание помогут определиться
                ul.certificates__variants-list
                    li.certificates__variant-item
                        p.certificates__variant-heading SSL для сайта Comodo PositiveSSL
                        p.certificates__variant-heading Comodo PositiveSSL
                        ul
                            li.certificates__variant-options Доступен физическим лицам
                            li.certificates__variant-options Защита 1го домена
                            li.certificates__variant-options Поддержка IDN доменов
                            li.certificates__variant-options Низкая степень доверия
                            li.certificates__variant-options Совместимость с браузерами: 96%
                            li.certificates__variant-options Автоустановка на наш хостинг
                        p <span class="certificates__price">900 р</span>/ год
                a(href="").orange-btn Заказать SSL сертификат


        .section-domain-names
            .container.domain-names-container
                h2.h2.domain-names-h2 Доменные имена
                div.domain-names__left-part
                    p.domain-names__left-part--text Правильное название сайта — залог трафика и успешной рекламы.  Домен должен ассоциироваться у пользователя с конкретными услугами или отраслью.
                    p.domain-names__left-part--text Часто говорят: «Посмотри на auto.ru» и становится понятно, что речь про ресурс, который связан с автомобилями. Точно так же и с другими сайтами, в имени которых заложен смысл их деятельности.
                    p.domain-names__left-part--text Помимо основных, выделяют специальные - тематические зоны: .travel, .site, .pro и т.д.
                    a(href="").orange-btn Подобрать и зарегистрировать домен
                div.domain-names__right-part
                    ul.domain-names__price-list
                        li.domain-names__price-item
                            p.domain-names__area .RU
                            p.domain-names__price 600Р
                            p.domain-names__term в год

            .section-servers
                h2.h2.servers-h2 Хостинг VPS/VDS серверов
                img(src="./assets/server.png").servers-img
                div.servers__description
                    p.servers__text Готовые тарифы VPS сбалансированы по производительности. Индивидуальная конфигурация позволит получить оптимальное количество ресурсов с оплатой за час.
                    p.servers__text Все тарифы VPS хостинга построены на оборудовании Xeon Scalable Silver/Gold.
                    p.servers__text Серверы размещены в DDoS-защищенном кластере ЦОД Tier lll и подключены к точке обмена трафиком Cloud-IX.
                div.servers__options-wrapper
                    h3.h3 Цены на VPS KVM
                    p.servers__options-description На каждом VPS сервере для вас уже включено:
                    ul.servers__options-list
                        li.servers__option-item Root-доступ
                        li.servers__option-item Защиты от DDoS
                        li.servers__option-item Домен в подарок при оплате за 1 год
                table.servers__table


        .section-benefits
            .container
                h2.h2 Выгоды нашего хостинга для Вас
                ul.benefits__benefits-list
                    li.benefits__benefits-item
                        img(src="./assets/benefits1.svg")
                        p.benefits__item-heading Низкие цены
                        p.benefits__item-description Доступные цены всегда были приоритетом нашей компании. Партнерская программа поможет сэкономить ещё больше.


        .sections-wrapper
            .section-reviews
                .container.reviews-container
                    div.reviews__about-us
                        h3.h3 Отзывы о нашем хостинге
                        p.reviews__text Хостинг – наша работа! Более 10 лет мы размещаем сайты своих клиентов на надёжном и современном оборудовании.
                        p.reviews__text Почитайте, что говорят наши клиенты
                    div.reviews-swiper swiperrrr

                    .section-questions
                        h2.h2.questions-h2 Вопросы и ответы
                        p.questions__text Здесь представлены самые популярные вопросы, которые задают нам клиенты перед оформлением заказа на виртуальный хостинг. Если вы не нашли ответ на имеющиеся у вас вопрос, задайте его нашим специалистам.
                        div.questions__tabs tabsss

            .section-stocks
                .container.stocks-container
                    p Получите 30 дней на тестирование нашего хостинга бесплатно
                    p  Плюс, 100% гарантия возврата всех оплаченных денежных средств в этот период.
                    a(href="").orange-btn Попробовать хостинг

            .section-payments
                .container
                    h2.h2 Способы оплаты
                    p.payments__text Оплачивайте услуги виртуального хостинга WSHOST любым, удобным для вас методом. Наш хостинг также могут заказать и оплатить юридические лица безналичным переводом
                    ul
                        li
                            img(src="./assets/1.svg")
                        li
                            img(src="./assets/2.svg")
                        li
                            img(src="./assets/3.svg")
                        li
                            img(src="./assets/4.svg")
                        li
                            img(src="./assets/5.svg")
                        li
                            img(src="./assets/6.svg")
                        li
                            img(src="./assets/7.svg")

        footer.footer
            .container.footer-container
                div
                    a(href="").footer__logo.logo
                    p.footer__left-content WSHOST даёт возможность купить хостинг сайтов дешево с SSL и полноценным пакетом услуг. Дешевая регистрация доменов и недорогой хостинг позволяют создать сайт любой тематики. Мы занимаем лидирующие позиции в даной сфере. Нашими клиентами являются жители городов Москва, Санкт-Петербург и т.д. Выбирая наш php хостинг вы получаете премиум услуги по низкой цене.
                    div.footer__left-content-wrapper
                        div
                            p.footer__left-content-heading О компании
                            ul.footer__info-list
                                li.footer__info-item
                                    a(href="").footer__info-link О хостинг-провайдере
                                li
                                    a(href="").footer__info-link Партнёрская программа
                                li
                                    a(href="").footer__info-link Дата-центр
                                li
                                    a(href="").footer__info-link Документы для клиентов
                                li
                                    a(href="").footer__info-link Договор на услуги хостинга
                                li
                                    a(href="").footer__info-link Способы оплаты
                                li
                                    a(href="").footer__info-link Цены
                                li
                                    a(href="").footer__info-link Акции
                                li
                                    a(href="").footer__info-link Новости
                                li
                                    a(href="").footer__info-link Вакансии
                                li
                                    a(href="").footer__info-link Контакты
                        div
                            p.footer__left-content-heading Наши услуги
                            ul
                                li
                                    a(href="").footer__info-link Виртуальный хостинг
                                li
                                    a(href="").footer__info-link Хостинг для 1С-Битрикс
                                li
                                    a(href="").footer__info-link Хостинг для Wordpress
                                li
                                    a(href="").footer__info-link Аренда VPS
                                li
                                    a(href="").footer__info-link Регистрация доменов
                                li
                                    a(href="").footer__info-link SSL сертификаты
                                li
                                    a(href="").footer__info-link Конструктор сайтов

                ul
                    li
                        a(href="")
                            p Телефон в Москве:
                            p +7 (495) 123-45-56
                    li
                        a(href="")
                            p Телефон в Москве:
                            p +7 (495) 123-45-56
                    li
                        a(href="")
                            p Телефон в Москве:
                            p +7 (495) 123-45-56
                    li Tехническая поддержка работает 24/7

                div
                    ul.socials__list
                        li.socials__item
                            a(href="").socials__link.socials__link--twitter
                        li.socials__item
                            a(href="").socials__link.socials__link--insta
                        li.socials__item
                            a(href="").socials__link.socials__link--vk
                        li.socials__item
                            a(href="").socials__link.socials__link--fb
                    button.footer__btn Report Spam

                div
                    p © 2007-2021 ООО "Вебсайт хостинг". Все права защищены.
                    p Политика конфиденциальности





</template>

<script>

    import Column from "./components/column";

    export default {

        created () {
            console.log(Object.values(this.countries))
        },
        destroyed () {
        },
        methods: {
        },

        data (){
            return {
                name: '',
                tel: '',
                email: '',
            }
        },
        name: 'App',
        components: {
            Column
        },
    }



</script>

<style lang="scss">
    @import "./assets/scss/general.scss";

    /*header*/
    .header {
        padding: 10px 130px;
        background-color: $blackColor;
    }

    .header-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        justify-content: center;
        align-items: center;
    }

    .logo {
        display: block;
        width: 143px;
        height: 88px;
        background: transparent url("./assets/logo.svg") no-repeat center;
    }

    .header-contacts {
        display: flex;
        flex-direction: column;
    }

    .header__link {
        position: relative;
        font-weight: 400;
        font-size: 16px;
        color: $whiteColor;
        padding-left: 40px;

        &:before {
            content: '';
            position: absolute;
            width: 28px;
            height: 28px;
            left: 0;
        }
    }

    .header__link--phone {
        &:before {
            background: transparent url("./assets/phone_icon.svg") no-repeat center;
        }
    }

    .header__link--email {
        &:before {
            background: transparent url("./assets/mail_icon.svg") no-repeat center;
        }
    }

    .header__right-part {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .header__button-buy {
        background-color: $blueColor;
        padding: 7px 40px;
        color: $whiteColor;
        margin-right: 36px;
    }

    .header__link--account {
        display: block;
        width: 44px;
        height: 44px;
        background: transparent url("./assets/account.svg") no-repeat center;
    }





    /*section-nav*/
    .section-nav {
        background: $whiteColor;
        padding: 16px 130px;
    }

    .nav__list {
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        justify-content: center;
        align-items: center;
    }

    .nav__item {
        position: relative;
        text-align: center;

        &:not(:last-child):after {
            content: '|';
            position: absolute;
            right: 0;
            color: $lightGrayColor;
        }
    }

    .nav__link {
        @include mainTextStyle;
        width: 100%;
        display: inline-block;
        padding: 0 30px;
        white-space: nowrap;
        text-transform: uppercase;
        color: $blackColor;
    }



    /*section-about*/
    .section-about {
        padding: 64px 130px;
        background: linear-gradient(91.05deg, #5994BA 14.15%, #ADCCE0 99%);
    }

    .about-container {
        background: transparent url("./assets/about.svg") no-repeat center;
    }

    .about__h1 {
        font-weight: 500;
        font-size: 72px;
        line-height: 100%;
        letter-spacing: 0.06em;
        color: $whiteColor;
        text-shadow: 3px 1px 0 #3E708F;
    }

    .about__p {
        @include mainTextStyle;
        color: $whiteColor;
    }

    .about__p--normal {
        font-weight: 400;
    }

    .about__p--bold {
        font-weight: 600;
    }



   /*section-rates*/
    .section-rates {
        background-color: #F8F8F8;
    }

    .rates__text {
        @include mainTextStyle;
        color: $darkGreyColor;
    }

    .bold-text {
        font-weight: 600;
    }

    .rates__type-list {
        display: flex;
    }

    .rates__type-item {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        min-width: 280px;
        min-height: 190px;
        padding: 20px;
        background-color: $whiteColor;
        box-shadow: 0 4px 4px rgba(183, 183, 183, 0.43);
        border-radius: 10px 10px 0 0;
    }

    .rates__type-heading {
        font-weight: 600;
        font-size: 36px;
        line-height: 150%;
        letter-spacing: 0.05em;
        text-transform: uppercase;
        color: #1B567C;
        opacity: 0.8;
    }

    .rates__description {
        @include mainTextStyle;
        color: $darkGreyColor;
    }

    .rates__option-list {
        display: flex;
    }

    .rates__option-item {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        min-width: 280px;
        padding: 20px;
        background-color: $whiteColor;
        box-shadow: 0 4px 4px rgba(183, 183, 183, 0.43);
        border-radius: 0 0 10px 10px;
    }

    .rates__memory {
        font-weight: 600;
        font-size: 20px;
    }

    .rates__option {
        font-weight: 400;
        font-size: 16px;
        line-height: 150%;
        text-align: center;
        color: #858585;
    }

    .rates__price-wrapper {
        background: linear-gradient(270deg, rgba(255,255,255,1) 0%, rgba(124,180,216,1) 100%);
    }

    .rates__btn-buy-host {
        width: 232px;
        height: 44px;
        text-align: center;
        color: $whiteColor;
        background-color: $blueColor;
    }

    .rates__btn-all-options {
        font-style: italic;
        font-weight: 400;
        font-size: 16px;
        text-decoration: underline;
        color: $orangeColor;
    }



   /*section-advantages*/
    .section-advantages{
        background-color: #F8F8F8;
        padding: 65px 130px 90px;
    }

    .advantages__text {
        position: relative;
        font-weight: 600;
        font-size: 20px;
        color: #1B567C;
        padding-left: 40px;

        &:before {
            content: '';
            position: absolute;
            left: 0;
            width: 32px;
            height: 32px;
            background: transparent url("./assets/check.svg") no-repeat center;
        }
    }

    .advantages-container {
        display: flex;
        align-items: center;
    }




    /*section-cms*/
    .section-cms {
        padding: 48px 130px 86px;
        background: rgb(219,232,240);
        background: linear-gradient(135deg, rgba(219,232,240,1) 0%, rgba(219,232,240,1) 50%, rgba(196,219,234,1) 50%, rgba(196,219,234,1) 100%);
    }

    .cms-h2 {
        margin-bottom: 60px;
    }

    .cms__content {
        margin-bottom: 70px;
    }



        /*section-certificates*/

    .section-certificates {
        background-color: #F8F8F8;
        padding: 90px 130px;
    }

    .certificates__description {
            margin-bottom: 20px;
    }

    .certificates__variants-list {

    }

    .certificates__variant-item {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        width: 25%;
        height: 551px;
        padding: 40px 45px;
        background: rgba(103, 168, 210, 0.1);
        border: 1px solid rgba(103, 168, 210, 0.3);
        box-shadow: 0 4px 4px rgba(183, 183, 183, 0.43);
        border-radius: 10px;
        text-align: center;
    }

    .certificates__variant-heading {
        color: #1B567C;
        font-weight: 600;
        font-size: 20px;
    }

    .certificates__variant-options {
        font-weight: 400;
        font-size: 16px;
    }

    .certificates__price {
        color: #1B567C;
        font-weight: 600;
        font-size: 24px;
    }

    .certificates__btn {
        display: block;
        margin: 0 auto;
        width: fit-content;
    }


        /**/
    .section-domain-names{
        background: linear-gradient(180deg, rgba(124, 180, 216, 0.4) 0%, rgba(191, 230, 255, 0) 100%);
        padding: 50px 130px;
    }

    .domain-names-container {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(2, auto);
    }

    .domain-names-h2 {
        grid-area: 1/1/2/3;
        justify-self: center;
    }

    .domain-names__left-part {
        grid-area: 2/1/3/2;
    }

    .domain-names__right-part {
        grid-area: 2/2/3/3;
    }

    .domain-names__left-part--text {
        margin-bottom: 20px;
    }

    .domain-names__price-item {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(2, 1fr);
        max-width: 280px;
        background: $whiteColor;
        box-shadow: 0 4px 4px rgba(183, 183, 183, 0.43);
        border-radius: 5px;
        margin-bottom: 20px;
        padding: 17px 20px;
    }

    .domain-names__area {
        grid-area: 1/1/3/2;
        align-self: center;
        position: relative;
        font-weight: 600;
        font-size: 24px;
        letter-spacing: 0.05em;
        text-transform: uppercase;
        color: #1B567C;

        &:before {
            content: '';
            position: absolute;
            left: 0;
            width: 55px;
            height: 55px;
            background: transparent url("./assets/Ellipse.svg") no-repeat center;
        }
    }

    .domain-names__price {
        grid-area: 1/2/2/3;
        font-weight: 600;
        font-size: 24px;
        text-align: center;
        letter-spacing: 0.05em;
        text-transform: uppercase;
        color: $darkGreyColor;
    }

    .domain-names__term {
        @include mainTextStyle;
        grid-area: 2/2/3/3;
        text-align: center;
        color: $darkGreyColor;
    }




        /*section-servers*/

    .section-servers {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }

    .servers-h2 {
        grid-area: 1/1/2/3;
        justify-self: center;
    }

    .servers-img {
        grid-area: 2/1/3/2;
    }

    .servers__description {
        grid-area: 2/2/3/3;
    }

    .servers__text {
        margin-bottom: 20px;
    }

    .servers__options-wrapper {
        grid-area: 3/1/4/2;
    }

    .servers__options-description {
        @include mainTextStyle;
        color: #3C3B3B;
    }

    .servers__option-item {
        position: relative;
        font-weight: 600;
        font-size: 20px;
        color: #1B567C;
        padding-left: 40px;

        &:before {
            content: '';
            position: absolute;
            left: 0;
            width: 32px;
            height: 32px;
            background: transparent url("./assets/check.svg") no-repeat center;
        }
    }

    .servers__table {
        grid-area: 3/2/4/3;
    }


    /**/
    .section-benefits {
        background-color: #DBE8F0;
    }

    .benefits__benefits-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .benefits__item-heading {
        font-weight: 600;
        font-size: 20px;
        text-align: center;
        color: $blackColor;
    }

    .benefits__item-description {
        max-width: 276px;
        font-weight: 400;
        font-size: 16px;
        text-align: center;
        color: #858585;
    }





    /*section-reviews*/

    .sections-wrapper {
        display: grid;
        grid-template-rows: repeat(2, auto);
    }

    .section-reviews {
        grid-area: 1/1/2/3;
        display: grid;
        grid-template-rows: repeat(2, auto);
        background-color: #F8F8F8;
        padding: 105px 130px 120px;
    }

    .reviews__about-us {
        grid-area: 1/1/2/2;
    }

    .reviews-swiper {
        grid-area: 1/2/2/3;
    }

    .reviews-container {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }

    .reviews__text {
        @include mainTextStyle;
    }
        /**/
    .section-questions {
        grid-area:  1/1/3/3;
    }

    .questions__text {
        @include mainTextStyle;
    }

    .section-questions {
        grid-area: 2/1/3/3;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }

    .questions-h2 {
        grid-area: 1/1/2/3;
        justify-self: center;
    }

    .questions__text {
        grid-area: 2/1/3/3;
    }

    .questions__tabs {
        grid-area: 3/1/4/3;
    }

        /*section-stocks*/

    .section-stocks {
        grid-area:  2/1/4/3;
        box-shadow: 0 4px 4px rgba(46, 46, 46, 0.27);
        border-radius: 10px;
        padding: 64px 40px 55px;
        color: $whiteColor;
        text-align: center;
    }

    .stocks-container {
        background: #1B567C;
    }


        /*section-payments*/

    .section-payments {
        grid-area: 2/1/3/3;
        background: linear-gradient(180deg, rgba(124, 180, 216, 0.4) 0%, rgba(191, 230, 255, 0) 100%);
    }

    .payments__text {
        @include mainTextStyle;
    }


        /**/
    .footer {
        background: #262626;
        color: $whiteColor;
    }

    .footer__logo {
        margin-bottom: 15px;
    }

    .footer__left-content {
        color: #858585;
        margin-bottom: 68px;
    }

    .footer-container {
        display: grid;
        grid-template-columns: 50% 25% 25%;
        padding: 90px 130px 30px;
    }

    .footer__left-content-wrapper {
        display: flex;
        justify-content: space-between;
    }

    .footer__left-content-heading {
        font-weight: 600;
        font-size: 20px;
        color: #858585;
    }

    .socials__list {
        display: flex;
        gap: 20px;
    }

    .socials__link {
        display: inline-block;
        width: 48px;
        height: 48px;
    }

    .socials__link--twitter{
        background: transparent url("./assets/socials1.svg") no-repeat center;
    }

    .socials__link--insta{
        background: transparent url("./assets/socials2.svg") no-repeat center;
    }

    .socials__link--vk{
        background: transparent url("./assets/socials3.svg") no-repeat center;
    }

    .socials__link--fb{
        background: transparent url("./assets/socials4.svg") no-repeat center;
    }

    .footer__left-links {
        font-weight: 400;
        font-size: 16px;
        line-height: 150%;
        color: $whiteColor;
    }

    .footer__btn {
        background-color: #67A8D2;
    }



</style>
