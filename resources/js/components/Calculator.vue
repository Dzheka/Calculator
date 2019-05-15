<template>
    <div class="container">
        <table class="table table-bordered">
            <tr>
                <th>Визитки 20x55мм</th>
                <th>50 шт.</th>
                <th>100 шт.</th>
                <th>300 шт.</th>
                <th>500 шт.</th>
                <th>1000 шт.</th>
                <th>3000 шт.</th>
                <th>5000 шт.</th>
                <th>10000 шт.</th>
            </tr>
            <tr>
                <th>#01 БЕЛЫЙ БЛЕСК 350г</th>
                <td align="center">
                    <!--<cell-input :name="vizitki.blesk50"-->
                    <!--&gt;</cell-input>-->
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#02 ЗОЛОТО 350г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#03 СЕРЕБРО 350г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#04 СЕРЕБРИСТЫЙ СИЛК 320г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#05 БЕЛЫЙ ЛИОН 350г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#06 ЁЛОЧКА 350г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#07 МАТОВАЯ БУМАГА 300г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#08 МАТОВАЯ ЛАМИНАЦИЯ 350г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#09 ГЛЯНЦЕВАЯ БУМАГА 350г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>#10 ПЛАСТИК 500г</th>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
        </table>

        <table class="table table-bordered">
            <tr>
                <th>ФЛАЕР (евро) 210х100мм</th>
                <th>50 шт.</th>
                <th>100 шт.</th>
                <th>300 шт.</th>
                <th>500 шт.</th>
                <th>1000 шт.</th>
                <th>3000 шт.</th>
                <th>5000 шт.</th>
                <th>10000 шт.</th>
            </tr>
            <tr>
                <th>Мелованная стр. печать 135г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 200г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 115г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
        </table>

        <table class="table table-bordered">
            <tr>
                <th>ФЛАЕР (А6) 140х105мм</th>
                <th>50 шт.</th>
                <th>100 шт.</th>
                <th>300 шт.</th>
                <th>500 шт.</th>
                <th>1000 шт.</th>
                <th>3000 шт.</th>
                <th>5000 шт.</th>
                <th>10000 шт.</th>
            </tr>
            <tr>
                <th>Мелованная стр. печать 135г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 200г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 115г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
        </table>

        <table class="table table-bordered">
            <tr>
                <th>ФЛАЕР (А5) 210х105мм</th>
                <th>50 шт.</th>
                <th>100 шт.</th>
                <th>300 шт.</th>
                <th>500 шт.</th>
                <th>1000 шт.</th>
                <th>3000 шт.</th>
                <th>5000 шт.</th>
                <th>10000 шт.</th>
            </tr>
            <tr>
                <th>Мелованная стр. печать 135г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 200г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 115г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
        </table>

        <table class="table table-bordered">
            <tr>
                <th>Постер (А4) 297х210мм</th>
                <th>50 шт.</th>
                <th>100 шт.</th>
                <th>300 шт.</th>
                <th>500 шт.</th>
                <th>1000 шт.</th>
                <th>3000 шт.</th>
                <th>5000 шт.</th>
                <th>10000 шт.</th>
            </tr>
            <tr>
                <th>Мелованная стр. печать 135/160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 200г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 250/350г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 135г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Биговка в 2 сгиба</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
        </table>

        <table class="table table-bordered">
            <tr>
                <th>Постер (А4) 297х210мм</th>
                <th>50 шт.</th>
                <th>100 шт.</th>
                <th>300 шт.</th>
                <th>500 шт.</th>
                <th>1000 шт.</th>
                <th>3000 шт.</th>
                <th>5000 шт.</th>
                <th>10000 шт.</th>
            </tr>
            <tr>
                <th>Мелованная стр. печать 135/160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 200г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная стр. печать 250/350г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 135г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Мелованная лаз. печать 160г.</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
            <tr>
                <th>Биговка в 2 сгиба</th>
                <td align="center">
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk50">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk100">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk300">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk500">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk1000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk3000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk5000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
                <td>
                    <div class="toggle">
                        <input type="checkbox" class="check" v-model="blesk10000">
                        <b class="b switch"></b>
                        <b class="b track"></b>
                    </div>
                </td>
            </tr>
        </table>
        <div class="row">
            <div class="col">
                <input type="text" v-model="firstValue"  class="form-control" placeholder="0">
        </div>
            <div class="col">
                <input type="text" v-model="secondValue" class="form-control" placeholder="0">
            </div>
        </div>
        <div class="row mt-5">
            <button class="btn btn-primary ml-1" type="submit" @click="sum">Сложить</button>
            <button class="btn btn-primary ml-1" type="submit" @click="multiply">умножить</button>

            <span class="ml-5">Результат: {{ totalValue }}</span>
        </div>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                firstValue: null,
                secondValue: null,
                vizitki: {
                    blesk50: null,
                    blesk100: null,
                    blesk300: null,
                    blesk500: null,
                    blesk1000: null,
                    blesk3000: null,
                    blesk5000: null,
                    blesk10000: null
                },
                flaer_evro: {
                    blesk50: null,
                    blesk100: null,
                    blesk300: null,
                    blesk500: null,
                    blesk1000: null,
                    blesk3000: null,
                    blesk5000: null,
                    blesk10000: null
                },
                flaer_a6: {
                    blesk50: null,
                    blesk100: null,
                    blesk300: null,
                    blesk500: null,
                    blesk1000: null,
                    blesk3000: null,
                    blesk5000: null,
                    blesk10000: null
                },
                flaer_a5: {
                    blesk50: null,
                    blesk100: null,
                    blesk300: null,
                    blesk500: null,
                    blesk1000: null,
                    blesk3000: null,
                    blesk5000: null,
                    blesk10000: null
                },
                poster_a4: {
                    blesk50: null,
                    blesk100: null,
                    blesk300: null,
                    blesk500: null,
                    blesk1000: null,
                    blesk3000: null,
                    blesk5000: null,
                    blesk10000: null
                },
                totalValue: ''
            }
        },
        methods:{
            sum() {
                this.totalValue = parseInt(this.firstValue) + parseInt(this.secondValue)
            },
            multiply(){
                this.totalValue = parseInt(this.firstValue) * parseInt(this.secondValue)
        },
        }
    }
</script>
<style>
    th{
        background: #E6E6FA;
        font-size: 10px;
        height: 10px;
    }
    td{
        font-size: 10px;
        height: 10px;
    }
    * {
        margin: 0;
        padding: 0;
        position: relative;
        box-sizing: border-box;
    }

    html, body {
        height: 100%;
    }

    .b {
        display: block;
    }

    .toggle {
        position: absolute;
        top: 50%;
        left: 50%;
        width: 40px;
        height: 25px;
        border-radius: 100px;
        background-color: #ddd;
        margin: -10px -20px;
        overflow: hidden;
        box-shadow: inset 0 0 2px 1px rgba(0,0,0,.05);
    }

    .check {
        position: absolute;
        display: block;
        cursor: pointer;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        opacity: 0;
        z-index: 6;
    }

    .check:checked ~ .track {
        box-shadow: inset 0 0 0 20px #4bd863;
    }

    .check:checked ~ .switch {
        right: 2px;
        left: 22px;
        transition: .35s cubic-bezier(0.785, 0.135, 0.150, 0.860);
        transition-property: left, right;
        transition-delay: .05s, 0s;
    }

    .switch {
        position: absolute;
        left: 2px;
        top: 2px;
        bottom: 2px;
        right: 22px;
        background-color: #fff;
        border-radius: 36px;
        z-index: 1;
        transition: .35s cubic-bezier(0.785, 0.135, 0.150, 0.860);
        transition-property: left, right;
        transition-delay: 0s, .05s;
        box-shadow: 0 1px 2px rgba(0,0,0,.2);
    }

    .track {
        position: absolute;
        left: 0;
        top: 0;
        right: 0;
        bottom: 0;
        transition: .35s cubic-bezier(0.785, 0.135, 0.150, 0.860);
        box-shadow: inset 0 0 0 2px rgba(0,0,0,.05);
        border-radius: 40px;
    }
</style>
