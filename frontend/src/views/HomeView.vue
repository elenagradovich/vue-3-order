<template>
    <main class="content">
        <form action="#" method="post">
            <div class="content__wrapper">
                <h1 class="title title--big">Pizza Builder</h1>
                <div class="content__dough">
                    <div class="sheet">
                        <h2 class="title title--small sheet__title">Choose the dough</h2>
                        <div class="sheet__content dough">
                            <label class="dough__input dough__input--light">
                                <input type="radio" name="dought" value="light" class="visually-hidden" checked>
                                <b>Thin</b>
                                <span>Made from hard wheat</span>
                            </label>
                            <label class="dough__input dough__input--large">
                                <input type="radio" name="dought" value="large" class="visually-hidden">
                                <b>Thick</b>
                                <span>Made from hard wheat</span>
                            </label>
                        </div>
                    </div>
                </div>
                <div class="content__diameter">
                    <div class="sheet">
                        <h2 class="title title--small sheet__title">Choose the size</h2>

                        <div class="sheet__content diameter">
                            <label class="diameter__input diameter__input--small">
                                <input type="radio" name="diameter" value="small" class="visually-hidden">
                                <span>23 cm</span>
                            </label>
                            <label class="diameter__input diameter__input--normal">
                                <input type="radio" name="diameter" value="normal" class="visually-hidden" checked>
                                <span>32 cm</span>
                            </label>
                            <label class="diameter__input diameter__input--big">
                                <input type="radio" name="diameter" value="big" class="visually-hidden">
                                <span>45 cm</span>
                            </label>
                        </div>
                    </div>
                </div>
                <div class="content__ingredients">
                    <div class="sheet">
                        <h2 class="title title--small sheet__title">Choose the ingredients</h2>

                        <div class="sheet__content ingredients">

                            <div class="ingredients__sauce">
                                <p>Base sauce:</p>

                                <label class="radio ingredients__input">
                                    <input type="radio" name="sauce" value="tomato" checked>
                                    <span>Tomato</span>
                                </label>
                                <label class="radio ingredients__input">
                                    <input type="radio" name="sauce" value="creamy">
                                    <span>Creamy</span>
                                </label>
                            </div>

                            <div class="ingredients__filling">
                                <p>Toppings:</p>

                                <ul class="ingredients__list">
                                    <li class="ingredients__item">
                                        <span class="filling filling--mushrooms">Mushrooms</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--cheddar">Cheddar</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--salami">Salami</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--ham">Ham</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--ananas">Pineapple</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--bacon">Bacon</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--onion">Onion</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--chile">Chili</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--jalapeno">Jalapeño</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--olives">Olives</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--tomatoes">Tomatoes</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--salmon">Salmon</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--mozzarella">Mozzarella</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--parmesan">Parmesan</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                    <li class="ingredients__item">
                                        <span class="filling filling--blue_cheese">Blue cheese</span>

                                        <div class="counter counter--orange ingredients__counter">
                                            <button type="button" class="counter__button counter__button--minus" disabled>
                                                <span class="visually-hidden">Less</span>
                                            </button>
                                            <input type="text" name="counter" class="counter__input" value="0">
                                            <button type="button" class="counter__button counter__button--plus">
                                                <span class="visually-hidden">More</span>
                                            </button>
                                        </div>
                                    </li>

                                </ul>

                            </div>

                        </div>
                    </div>
                </div>
                <div class="content__pizza">
                    <label class="input">
                        <span class="visually-hidden">Pizza name</span>
                        <input type="text" name="pizza_name" placeholder="Enter pizza name">
                    </label>
                    <div class="content__constructor">
                        <div class="pizza pizza--foundation--big-tomato">
                            <div class="pizza__wrapper">
                                <div class="pizza__filling pizza__filling--ananas"></div>
                                <div class="pizza__filling pizza__filling--bacon"></div>
                                <div class="pizza__filling pizza__filling--cheddar"></div>
                            </div>
                        </div>
                    </div>
                    <div class="content__result">
                        <p>Total: 0 $</p>
                        <button type="button" class="button" disabled>Cook!</button>
                    </div>
                </div>
            </div>
        </form>
    </main>
</template>
