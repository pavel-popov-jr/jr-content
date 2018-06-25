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
