# Useful links and codes for me

Just a few links I always need, maybe they can help you, maybe not.

- [Markdown Helper repository](https://github.com/luong-komorebi/Markdown-Tutorial/blob/master/README_pt-BR.md#tools)
- [Git Tutorial](https://github.com/rafaballerini/GitTutorial)
- Font Awesome 5
```html
<!-- END OF THE BODY -->
<script
  src="https://kit.fontawesome.com/4caf299d90.js"
  crossorigin="anonymous"
></script>
```

- Feather Icons
```html
<!-- HEAD -->
<script src="https://unpkg.com/feather-icons"></script>

<!-- END OF THE BODY -->
<script>
  feather.replace();
</script>
```

- Bootstrap 5
```html
<!-- HEAD -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css"
  rel="stylesheet"
  integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x"
  crossorigin="anonymous"
/>

<!-- END OF THE BODY -->
<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
  crossorigin="anonymous"
></script>
```

- Success alert and redirect with meta tags in php
```php
echo '<script>alert("Updated successfully!
")</script>';
echo '<meta http-equiv="refresh" content="0;URL=\'/\'" />';
```

- Array weekDays and month
```js
const weekDays = [
  'Sun',
  'Mon',
  'Tue',
  'Wed',
  'Thu',
  'Fri',
  'Sat',
]
const month = [
  'Jan',
  'Feb',
  'Mar',
  'Apr',
  'May',
  'Jun',
  'Jul',
  'Aug',
  'Sep',
  'Oct',
  'Nov',
  'Dec'
]
```

- JS code to get Array of hours
```js
let listHour = []
for(var i = 0; i < 24; i++) {
    let hour = String(i).length == 1 ? '0' + String(i) : String(i)
    for(var j = 0; j < 6; j++) {
        let minute = String(j) + '0'
        listHour.push(hour + ':' + minute)
    }
}
```

- jQuery and jQuery Mask
```html
<!-- END OF THE BODY -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.mask/1.14.16/jquery.mask.min.js" integrity="sha512-pHVGpX7F/27yZ0ISY+VVjyULApbDlD0/X0rgGbTqCE7WFW5MezNTWG/dnhtbBuICzsd0WQPgpE4REBLv+UqChw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```
