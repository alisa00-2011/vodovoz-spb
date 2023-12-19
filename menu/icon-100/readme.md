В контейнере  v-header-main ссылку с логотипом вв обернуть в контейнер v-header-main__images и добавить в него svg  “100 лучших товаров России”. Код представлен в файле icon-100.html
<div class="v-header-main">
  <div class="container">
        Место вставки контейнера с лого и значком
        <div class="v-header-main__menu">
            …
        </div>
        <div class="v-header-main__contact">
        …
       </div>
  </div>
</div>
Далее в файле layout2023.css:
1.	В соответствующих местах добавить стили из файла style.css
2.	Убрать следующие стили из layout2023.css:
@media (max-width: 1199px) {
    .v-header-main__contact > a {
        font-size: 1.5rem;
    }
}

@media (min-width: 768px) {
body.scrolled .v-header-main__contact > a {
    font-size: 1.5rem;
}
} 


