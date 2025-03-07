---
title: Full Page Layout
layout: example
summary: Full page layout example using navigation, hero, cards, buttons, accordions, modals, and drawers.
skellyCSS: true
---


<header class="site-menu-wrapper px-3 background--black" style="height:100px">
  <a href="#" class="site-logo text--white text--size-lg text--bold flex h-100 flex flex--align-center">
    Planet Pizza
  </a>
  <button class="site-menu-mobile-action px-4 text--white">
    <span class="sr-only">Toggle Navigation</span>
    <i aria-hidden="true" focusable="false" class="pi-menu pi-xl"></i>
  </button>
  <nav class="site-menu text--white">
    <div class="dropdown">
      <a href="#" class="site-menu__item dropdown__trigger h-100">
        Item 1 
        <i class="ml-1 pi-angle-down" aria-hidden="true"></i>
      </a>
      <div class="dropdown__content">
        <a href="#" class="dropdown__content-item">Link 1</a>
        <a href="#" class="dropdown__content-item">Link 2</a>
        <a href="#" class="dropdown__content-item">Link 3</a>
        <a href="#" class="dropdown__content-item">Link 4</a>
      </div>
    </div>
    <a href="#" class="site-menu__item h-100">Item 2</a>
    <a href="#" class="site-menu__item h-100">Item 3</a>
    <a href="#" class="site-menu__item h-100">Item 4</a>
    <a href="#" class="site-menu__item h-100">Item 5</a>
  </nav>
</header>

<div
  class="background-image" 
  data-gradient-direction="to top"
  data-gradient-stop="transparent" 
  data-background-image="https://images.unsplash.com/photo-1590947132387-155cc02f3212?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80">
    <div class="background--black-a80 text--center py-4">
      <h1 class="text--size-3xl text--white text--bold">Planet Pizza</h1>
      <span class="text--white flex flex--justify-center text--size-lg">Otherworldly pizza!</span>
      <button class="button button--salmon text--white button--lg my-4 hover-scale">
        <span class="flex flex--align-center">
        <i class='pi-touch mr-2'></i>
        Order Online
        </span>
      </button>
      <p class="m-0">
        <i class="pi-angle-down text--white text--size-xl" aria-hidden="true"></i>
      </p>
     </div>
</div>

<div class="block-container mx-5 mt-5 mb-3">
  <h2 class="text--bold">Our Speciality Pizzas</h2>
</div>

<div class="block-container cards mx-5 pb-4">
  <div class="block tablet-up-6 laptop-up-3 p-2">
    <div class="card hover-shadow hover-scale">
      <img class="card__image" src="https://images.unsplash.com/photo-1584782930699-383ed067a486?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80" alt="Pepperoni Pizza" />
      <div class="card__content">
        <h3>Pepperoni</h3>
        <p class="skeleton" data-lines="5" role="presentation"></p>
        <button class="button button--salmon text--white">Add to Cart</button>
      </div> 
    </div>
  </div>
  <div class="block tablet-up-6 laptop-up-3 p-2">
    <div class="card hover-shadow hover-scale">
      <img class="card__image" src="https://images.unsplash.com/photo-1584782930699-383ed067a486?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80" alt="Pepperoni Pizza" />
      <div class="card__content">
        <h3>Ham & Pineapple</h3>
        <p class="skeleton" data-lines="5" role="presentation"></p>
        <button class="button button--salmon text--white">Add to Cart</button>
      </div> 
    </div>
  </div>
  <div class="block tablet-up-6 laptop-up-3 p-2">
    <div class="card hover-shadow hover-scale">
      <img class="card__image" src="https://images.unsplash.com/photo-1584782930699-383ed067a486?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80" alt="Pepperoni Pizza" />
      <div class="card__content">
        <h3>Bacon & Jalapeño</h3>
        <p class="skeleton" data-lines="5" role="presentation"></p>
        <button class="button button--salmon text--white">Add to Cart</button>
      </div> 
    </div>
  </div>
  <div class="block tablet-up-6 laptop-up-3 p-2">
    <div class="card hover-shadow hover-scale">
      <img class="card__image" src="https://images.unsplash.com/photo-1584782930699-383ed067a486?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80" alt="Pepperoni Pizza" />
      <div class="card__content">
        <h3>Three Cheese</h3>
        <p class="skeleton" data-lines="5" role="presentation"></p>
        <button class="button button--salmon text--white">Add to Cart</button>
      </div> 
    </div>
  </div>
</div>

<div class="px-3 py-6 text--center background--black-a80">
  <div class="block-container flex--justify-center mx-5">
    <div class="block block-8 text-black">
      <h2 class="text--white text--bold">Build your own Pizza!</h2>
      <button class="button button--salmon text--white button--lg modal__open hover-scale" data-modal="default-modal">Build Now</button>
    </div>
  </div>
</div>

<div class="block-container mx-5 pt-5">
  <h2 class="text--bold">Full Menu</h2>
</div>
<div class="block-container mx-5 pb-4">
  <div class="accordion block-12">
    <a href="#" class="accordion__header px-2 py-2 flex--justify-between flex--align-center">
      <h3 class="m-0 p-0">Appetizers</h3>
      <i class="pi-angle-down accordion__icon text--size-lg"></i>
    </a>
    <div class="accordion__content">
      <div class="block-container">
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Breadsticks</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Mozzarella Sticks</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>1/2 Dozen Wings</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Dozen Wings</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="accordion block-12">
    <a href="#" class="accordion__header px-2 py-2 flex--justify-between flex--align-center">
      <h3 class="m-0 p-0">Entrees</h3>
      <i class="pi-angle-down accordion__icon text--size-lg"></i>
    </a>
    <div class="accordion__content">
      <div class="block-container">
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Spaghetti</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Spaghetti & Meatballs</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Ravioli</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Chicken Parmesan</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="accordion block-12 mb-5">
    <a href="#" class="accordion__header px-2 py-2 flex--justify-between flex--align-center">
      <h3 class="m-0 p-0">Subs</h3>
      <i class="pi-angle-down accordion__icon text--size-lg"></i>
    </a>
    <div class="accordion__content">
      <div class="block-container">
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Italian</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Cheeseburger</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Turkey</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
        <div class="block tablet-up-6 laptop-up-3 p-2">
          <div class="card">
            <div class="card__content">
              <h4>Tuna Salad</h4>
              <p class="skeleton" data-lines="5" role="presentation"></p>
              <button class="button button--salmon text--white">Add to Cart</button>
            </div> 
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="default-modal" class="modal modal--closed">
  <div class="modal__inner">
    <div class="modal__header background--white">
      <h2 class="text--bold">Build your own Pizza</h2>
      <button class="button button--salmon text--white modal__close" data-modal="default-modal">
        Close 
        <i class="pi-times"></i>
      </button>
    </div>
    <div class="modal__content">
      <form action="" class="form">
        <div class="block-container mb-4">
          <fieldset class="pui-form__field block-4">
            <legend>Choose Size</legend>
            <div class="pui-toggle">
              <input id="Tall-2" type="radio" checked name="height">
              <label for="Tall-2">
                <i class='pi-check pi-heavy'></i> Personal
              </label>
              <input id="Short-2" type="radio" name="height">
              <label for="Short-2">
                <i class='pi-check pi-heavy'></i> Regular
              </label>
            </div>
          </fieldset>
        </div>
        <div class="block-container mb-4">
          <fieldset class="form__field">
            <legend>Choose Crust</legend>
            <div class="form__option-group">
              <input id="choose-small" type="radio" name="choose-one">
              <label for="choose-small">
                <div class="input-icons">
                  <i class='pi-circle pi-lg'></i>
                  <i class='pi-circle-solid'></i>
                </div>
                Pan
              </label>
              <input id="choose-bigger" type="radio" name="choose-one">
              <label for="choose-bigger">
                <div class="input-icons">
                  <i class='pi-circle pi-lg'></i>
                  <i class='pi-circle-solid'></i>
                </div>
                Garlic Pan
              </label>
            </div>
          </fieldset>
        </div>
        <div class="block-container mb-4">
          <fieldset class="form__field">
            <legend>Choose Toppings</legend>
            <div class="form__option-group">
              <input id="choose-this-one" type="checkbox">
              <label for="choose-this-one">
                <div class="input-icons">
                  <i class='pi-circle pi-lg'></i>
                  <i class='pi-check pi-heavy'></i>
                </div>
                Pepperoni
              </label>
              <input id="choose-that-one" type="checkbox">
              <label for="choose-that-one">
                <div class="input-icons">
                  <i class='pi-circle pi-lg'></i>
                  <i class='pi-check pi-heavy'></i>
                </div>
                Sausage
              </label>
              <input id="choose-that-one-2" type="checkbox">
              <label for="choose-that-one-2">
                <div class="input-icons">
                  <i class='pi-circle pi-lg'></i>
                  <i class='pi-check pi-heavy'></i>
                </div>
                Bacon
              </label>
              <input id="choose-that-one-3" type="checkbox">
              <label for="choose-that-one-3">
                <div class="input-icons">
                  <i class='pi-circle pi-lg'></i>
                  <i class='pi-check pi-heavy'></i>
                </div>
                Jalapeño
              </label>
            </div>
          </fieldset>
        </div>
        <div class="block-container">
          <button class="button button--salmon text--white mb-2">Add to Cart</button>
        </div>
      </form>
    </div>
  </div>
</div>

<div id="right" class="drawer drawer--closed drawer-right">
  <div class="drawer__inner">
    <div class="drawer__content">
      <div class="flex flex--justify-end">
      <button class="button button--salmon text--white drawer__close" data-drawer="right">
        Close 
        <i class="pi-times"></i>
      </button>
      </div>
      <ul class="list my-4">
        <li class="flex">
          <i class="pi-check mr-3 text--size-md"></i> 
          <p class="border-b border--color-lighter pb-2 mb-0 flex--grow">Pepperoni Pizza</p>
          <p>$15.00</p>
        </li>
        <li class="flex">
          <i class="pi-check mr-3 text--size-md"></i> 
          <p class="border-b border--color-lighter pb-2 mb-0 flex--grow">Breadsticks</p>
          <p>$5.00</p>
        </li>
        <li class="flex">
          <i class="pi-check mr-3 text--size-md"></i> 
          <p class="border-b border--color-lighter pb-2 mb-0 flex--grow">1/2 Dozen Wings</p>
          <p>$7.50</p>
        </li>
      </ul>
      <button class="button button--salmon text--white button--lg hover-scale">Checkout Now</button>
    </div>
  </div>
</div>

<div class="pos-fix pin-right pin-bottom p-4">
<button class="button button--salmon text--white button--lg drawer__open hover-scale" data-drawer="right">
  <i class='pi-tag mr-2'></i>
  View Cart
</button>
</div>

<footer class="px-3 py-4">
  <div class="block-container">
    <div class="block block-12 flex flex--column flex--justify-center flex--align-center">
      <p>Made with <span class="text--negative">&hearts;</span> and <a href="{{ .Site.Params.pui_url }}">Platform UI</a></p>
    </div>
  </div>
</footer>