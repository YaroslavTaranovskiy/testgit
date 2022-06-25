! +Tab = автоматично прописує розмітку Додати картинку можливо по абсолютному шляху ( вставляю ЮРЛ
картинки) <img scr="" alt="" /> - Щоб вставити картинку Картинка з ПК. Створили папку та закинули
туди картинку. прописуємо шлях в середині проекту

<form class="subscribe">
          <b class="title title-subscribe">Подпишитесь на рассылку</b>
          <div class="subscribe-form">
            <input type="email" name="user-mail" placeholder="E-mail" class="form-place">
            <button type="submit" class="btn-subscribe">
              <span class="btn-subscribe-text">Подписаться</span>
              <!-- <svg class="subscribe-icon" width="24" height="24">
                <use href="./imeges/icon/sprite.svg#icon-send-footer"></use>
              </svg> -->
            </button>
          </div>
        </form>

.btn-subscribe { width: 200px; height: 50px;

    cursor: pointer;

    background-color: var(--accent-color);

    display: flex;
    align-items: center;

    justify-content: center;

    border: none;
    border-radius: 4px;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);

    &::after {

        content: '';
        width: 24px;
        height: 24px;
        margin-left: 10px;
        background-size: contain;
        background-image: url('../imeges/icon/svg/send-footer.svg');
    }
