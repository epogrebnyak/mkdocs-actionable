# Роль хаос-тестов среди других видов тестирования

![изображение](https://user-images.githubusercontent.com/9265326/91170634-d8599100-e6e1-11ea-8cbe-c494d68efd18.png)


## Дополнительная информация по видам тестов

<table>
<thead>
<tr class="header">
<th><strong>Основной вопрос</strong></th>
<th><strong>Вид тестов</strong></th>
<th><strong>Типовая стадия</strong></th>
<th><strong>Учитывается ли риск сбоев инфраструктуры?</strong></th>
<th><strong>Что считать хорошим результатом?</strong></th>
<th><strong>Методология / направление</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Выполняет ли система заявленный функционал?</strong></td>
<td>Unit тесты, функциональные тесты</td>
<td>Разработка</td>
<td><center>Нет</center></td>
<td>Система соответствует спецификации</td>
<td>Test-driven development (TDD)</td>
</tr>
<tr class="even">
<td><strong>Устойчива ли система?</strong></td>
<td>Системные тесты</td>
<td>Ввод в эксплуатацию</td>
<td align="center"><center>Нет</center></td>
<td>В системе нет явно слабых мест и ошибок</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Достаточна ли производительность системы?</strong></td>
<td>Нагрузочные тесты</td>
<td>Ввод в эксплуатацию</td>
<td><center>Нет</center></td>
<td>Система держит пиковую нагрузку</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Как ведет себя система при случайном сбое ресурсов?</strong></td>
<td>Хаос-тесты</td>
<td>Эксплуатация</td>
<td><center>Да</center></td>
<td>Устойчивость или самовосстановление системы после инцидента</td>
<td>Chaos engineering</td>
</tr>
<tr class="odd">
<td><strong>Можем ли восстановить систему после сбоя?</strong></td>
<td>Аварийные учения</td>
<td>Эксплуатация</td>
<td><center>Да</center></td>
<td>Быстрый переход на резервную систему после инцидента</td>
<td>Disaster recovery (DR), business continuity (BC)</td>
</tr>
<tr class="even">
<td><strong>Защищена ли система от внешних атак?</strong></td>
<td>Пен-тесты</td>
<td>На разных стадиях</td>
<td><center>Обычно нет</center></td>
<td>Система защищена от внешней атаки</td>
<td>Информационная безопасность (infosec)</td>
</tr>
</tbody>
</table>