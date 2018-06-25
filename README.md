# Шпаргалка по разметке контента

## Таблицы

#### Обычная таблица (всегда растягивается на всю ширину контента) 
```html
<table>...</table>
```

#### Таблица с шириной по ее содержимому
```html
<table class="table table--auto-width">...</table>
```

#### Таблица зебра
```html
<table class="table table--striped">...</table>
```

#### Таблица пунктирная (все внутренние границы)
```html
<table class="table table--dashed">...</table>
```

#### Таблица пунктирная (только границы между строк)
```html
<table class="table table--dashed-rows">...</table>
```

#### Таблица пунктирная (только границы между ячеек)
```html
<table class="table table--dashed-cells">...</table>
```

#### Таблица с подзаголовками
Добавляем к нужному **`<tr>`** класс **`table__sub-head`**
```html
<table class="table">
  <tbody>
  <tr>
    <th>Array</th>
    <th>ArrayList</th>
  </tr>
  <tr class="table__sub-head">
    <td colspan="2" style="text-align: center;">Создание контейнера элементов</td>
  </tr>
  <tr>
    <td>
      <pre class="lecture-code language-java"><code>String[] list = new String[10];</code></pre>
    </td>
    <td>
      <pre class="lecture-code language-java"><code>ArrayList&ltString&gt list = new ArrayList&ltString&gt();</code></pre>
    </td>
  </tr>
  <tr class="table__sub-head">
    <td style="text-align: center;" colspan="2">Получение количества элементов</td>
  </tr>
  <tr>
    <td>
      <pre class="lecture-code language-java"><code>int n = list.length;</code></pre>
    </td>
    <td>
      <pre class="lecture-code language-java"><code>int n = list.size();</code></pre>
    </td>
  </tr>
  </tbody>
</table>
```

## Блок с кодом

#### Код с номерами строк
```html
<pre class="line-numbers language-java"><code>...</code></pre>
```

#### Код без номеров строк
```html
<pre class="language-java"><code>...</code></pre>
```

#### Код без номеров строк, увеличенный шрифт и отступы
```html
<pre class="lecture-code language-java"><code>...</code></pre>
```

#### Код с заголовком
```html
<div class="code-heading">Самая простая команда:</div>
<pre class="lecture-code language-java"><code>...</code></pre>
```

#### Код с шириной по содержимому
```html
<pre class="inline-block language-java"><code>...</code></pre>
```

#### Код с шириной по содержимому и с выравниванием по центру
```html
<div class="text-center">
  <pre class="inline-block language-java"><code>...</code></pre>
</div>
```

## Цитаты

#### Обычная цитата (выравнивается по правому краю)
```html
<blockquote>
  <p>«И взял Создатель металл и создал из него робота по образу и подобию своему.<br>
  И создал Он Java-программы – души роботов, и загрузил их в роботов, и оживил их».</p>
</blockquote>
```

#### Цитата с подписью
```html
<blockquote>
  <p>«И взял Создатель металл и создал из него робота по образу и подобию своему.<br>
  И создал Он Java-программы – души роботов, и загрузил их в роботов, и оживил их».</p>
  <footer>Инструкция к эксплуатации,<br><small>раздел 3, пункт 13.</small></footer>
</blockquote>
```
