<template>
    <div id="main" v-cloak>
        <h1 class="heading">Калькулятор</h1>

        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>Визитки </span>  <span>20x55мм</span>
                    </li>
                    <li class="head">
                        <span>#01 БЕЛЫЙ БЛЕСК </span> <span>350г</span>
                    </li>
                    <li class="head">
                        <span>#02 ЗОЛОТО </span> <span>350г</span>
                    </li>
                    <li class="head">
                        <span>#03 СЕРЕБРО </span> <span>350г</span>
                    </li>
                    <li class="head">
                        <span>#04 СЕРЕБРИСТЫЙ СИЛК </span> <span>320г</span>
                    </li>
                    <li class="head">
                        <span>#05 БЕЛЫЙ ЛИОН </span> <span>350г</span>
                    </li>
                    <li class="head">
                        <span>#06 ЁЛОЧКА </span> <span>350г</span>
                    </li>
                    <li class="head">
                        <span>#07 МАТОВАЯ БУМАГА </span> <span>300г</span>
                    </li>
                    <li class="head">
                        <span>#08 МАТОВАЯ ЛАМИНАЦИЯ </span> <span>350г</span>
                    </li>
                    <li class="head">
                        <span>#09 ГЛЯНЦЕВАЯ БУМАГА </span> <span>350г</span>
                    </li>
                    <li class="head">
                        <span>#10 ПЛАСТИК  </span> <span>500г</span>
                    </li>

                </td>
                <td>
                    <li class="head">
                        <span>50 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card50" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card100" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card300" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card500" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card1000" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card3000" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card5000" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="card in card10000" v-on:click="toggleActive(card)" v-bind:class="{ 'active' : card.active }">
                        <span>{{card.name}}</span> <span>{{card.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за визитки:</span> <span>{{totalCards()}}</span>
        </p>
        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>ФЛАЕР(ЕВРО) </span>  <span>210x100мм</span>
                    </li>
                    <li class="head">
                        <span>Мелованная стр. печать </span> <span>135г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>160г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>200г</span>
                    </li>
                    <li class="head">
                        <span>Меловаенная лаз. печать </span> <span>115г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>160г</span>
                    </li>

                </td>
                <td>
                    <li class="head">
                        <span>50 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro50" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro100" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro300" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro500" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro1000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro3000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro5000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerEvro10000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за Флаеры (Евро):</span> <span>{{totalFlaerEvro()}}</span>


        <p class="total">
            <span>Итоговая сумма за всё:</span> <span>{{totalCards() + totalFlaerEvro()}}</span>
        </p>
    </div>
</template>
<script>
    export default {
        data(){
            return {
                card50: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                card100: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                card300: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                card500: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                card1000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                card3000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                card5000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                card10000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro50: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro100: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro300: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro500: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro1000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro3000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro5000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
                flaerEvro10000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    },
                    {
                        name: 'по 200',
                        price: 250,
                        active: false
                    },
                    {
                        name: 'по 220',
                        price: 220,
                        active: false
                    },
                    {
                        name: 'по 250',
                        price: 220,
                        active: false
                    }
                ],
            }
        },
        methods: {
            toggleActive: function(s) {
                s.active = !s.active;
            },
            totalCards() {
                var total = 0;
                this.card50.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.card100.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.card300.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.card500.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.card1000.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.card3000.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.card5000.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.card10000.forEach(function(s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            },
            totalFlaerEvro() {
                var total = 0;
                this.flaerEvro50.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerEvro100.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerEvro300.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerEvro500.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerEvro1000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerEvro3000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerEvro5000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerEvro10000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            }
        },
    };
</script>