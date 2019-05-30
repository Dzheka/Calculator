<template>
    <div id="main">
        <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
        <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
        <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
        <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
        <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
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
        </p>
        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>ФЛАЕР(A6) </span>  <span>148x105мм</span>
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
                    <li class="services__item" v-for="flaer in flaerA650" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA6100" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA6300" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA6500" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA61000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA63000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA65000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA610000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за Флаеры (A6):</span> <span>{{totalFlaerA6()}}</span>
        </p>
        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>ФЛАЕР(A5) </span>  <span>210x105мм</span>
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
                    <li class="services__item" v-for="flaer in flaerA550" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA5100" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA5300" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA6500" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA51000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA53000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA55000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in flaerA510000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за Флаеры (A5):</span> <span>{{totalFlaerA5()}}</span>
        </p>
        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>Постер(A4) </span>  <span>297x210мм</span>
                    </li>
                    <li class="head">
                        <span>Мелованная стр. печать </span> <span>135/160г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>200г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>250/300г</span>
                    </li>
                    <li class="head">
                        <span>Меловаенная лаз. печать </span> <span>135г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>160г</span>
                    </li>
                    <li class="head">
                        <span>Биговка в 2 сгиба</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>50 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA450" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA4100" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA4300" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA4500" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA41000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA43000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA45000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA410000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за Постеры (А4):</span> <span>{{totalPosterA4()}}</span>
        </p>
        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>Постер(A3) </span>  <span>420x297мм</span>
                    </li>
                    <li class="head">
                        <span>Мелованная стр. печать </span> <span>160г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>200г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>250/350г</span>
                    </li>
                    <li class="head">
                        <span>Меловаенная лаз. печать </span> <span>135г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>170г</span>
                    </li>

                </td>
                <td>
                    <li class="head">
                        <span>50 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA350" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA3100" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA3300" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA3500" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA31000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA33000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA35000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA310000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за Постеры (A3):</span> <span>{{totalPosterA3()}}</span>
        </p>
        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>Постер(A2) </span>  <span>594x420мм</span>
                    </li>
                    <li class="head">
                        <span>Мелованная офсет. печать </span> <span>135/170г</span>
                    </li>
                    <li class="head">
                        <span> </span> <span>250/300г</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>50 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA250" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA2100" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA2300" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA2500" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA21000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA23000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA25000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA210000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за Постеры (A2):</span> <span>{{totalPosterA2()}}</span>
        </p>
        <ul class="services">
            <table>
                <td>
                    <li class="head">
                        <span>Постер(A1) </span>  <span>640x594мм</span>
                    </li>
                    <li class="head">
                        <span>ПВС внутренняя печать</span> <span>135/170г</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>50 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA150" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>100 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA1100" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>300 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA1300" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>500 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA1500" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>1000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA11000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>3000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA13000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>5000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA15000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
                <td>
                    <li class="head">
                        <span>10000 штук</span>
                    </li>
                    <li class="services__item" v-for="flaer in posterA110000" v-on:click="toggleActive(flaer)" v-bind:class="{ 'active' : flaer.active }">
                        <span>{{flaer.name}}</span> <span>{{flaer.price}}</span>
                    </li>
                </td>
            </table>
        </ul>
        <p class="total">
            <span>Итого за Постеры (A1):</span> <span>{{totalPosterA1()}}</span>
        </p>
        <p class="total">
            <span>Итоговая сумма за всё:</span> <span>{{totalCards() + totalFlaerEvro() + totalFlaerA5()
        + totalFlaerA6() + totalPosterA4() + totalPosterA3() + totalPosterA2() + totalPosterA1()}}</span>
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
                flaerA650: [
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
                flaerA6100: [
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
                flaerA6300: [
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
                flaerA6500: [
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
                flaerA61000: [
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
                flaerA63000: [
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
                flaerA65000: [
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
                flaerA610000: [
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
                flaerA550: [
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
                flaerA5100: [
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
                flaerA5300: [
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
                flaerA5500: [
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
                flaerA51000: [
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
                flaerA53000: [
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
                flaerA55000: [
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
                flaerA510000: [
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
                posterA450: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA4100: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA4300: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA4500: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA41000: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA43000: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA45000: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA410000: [
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
                        name: '+10%',
                        price: 0,
                        active: false
                    }
                ],
                posterA350: [
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
                posterA3100: [
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
                posterA3300: [
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
                posterA3500: [
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
                posterA31000: [
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
                posterA33000: [
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
                posterA35000: [
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
                posterA310000: [
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
                posterA250: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    }
                ],
                posterA2100: [
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
                ],
                posterA2300: [
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
                ],
                posterA2500: [
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
                ],
                posterA21000: [
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
                ],
                posterA23000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    }
                ],
                posterA25000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    }
                ],
                posterA210000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    },
                    {
                        name: 'по 100',
                        price: 400,
                        active: false
                    }
                ],

                posterA150: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    }
                ],
                posterA1100: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    }
                ],
                posterA1300: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    }
                ],
                posterA1500: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    }
                ],
                posterA11000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    }
                ],
                posterA13000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    }
                ],
                posterA15000: [
                    {
                        name: 'по 80',
                        price: 300,
                        active: false
                    }
                ],
                posterA110000: [
                    {
                        name: 'по 80',
                        price: 300,
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
            },
            totalFlaerA6() {
                var total = 0;
                this.flaerA650.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA6100.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA6300.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA6500.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA61000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA63000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA65000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA610000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            },
            totalFlaerA5() {
                var total = 0;
                this.flaerA550.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA5100.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA5300.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA5500.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA51000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA53000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA55000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.flaerA510000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            },
            totalPosterA4() {
                var total = 0;
                this.posterA450.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA4100.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA4300.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA4500.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA41000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA43000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA45000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA410000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            },

            totalPosterA3() {
                var total = 0;
                this.posterA350.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA3100.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA3300.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA3500.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA31000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA33000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA35000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA310000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            },
            totalPosterA2() {
                var total = 0;
                this.posterA250.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA2100.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA2300.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA2500.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA21000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA23000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA25000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA210000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            },

            totalPosterA1() {
                var total = 0;
                this.posterA150.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA1100.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA1300.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA1500.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA11000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA13000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA15000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                this.posterA110000.forEach(function (s) {
                    if (s.active) {
                        total += s.price;
                    }
                });
                return total;
            },
        },
    };
</script>