# tableview

```html
<!doctype html>
<title>TableView Example</title>

<script src=TableView.js></script>

<body>


<script>

var data = [
  {a:1,b:2,c:3},
  {a:10,b:20,c:30},
  {a:100,b:200,c:300}
]

var tv = new TableView(data);
document.body.appendChild(tv.render());
</script>
</body>
```

This will produce:


    <table>
      <thead>
        <tr>
          <th>a</th>
          <th>b</th>
          <th>c</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>2</td>
          <td>3</td>
        </tr>
        <tr>
          <td>10</td>
          <td>20</td>
          <td>30</td>
        </tr>
        <tr>
          <td>100</td>
          <td>200</td>
          <td>300</td>
        </tr>
      </tbody>
    </table>


<table>
  <thead>
    <tr>
      <th>a</th>
      <th>b</th>
      <th>c</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <td>10</td>
      <td>20</td>
      <td>30</td>
    </tr>
    <tr>
      <td>100</td>
      <td>200</td>
      <td>300</td>
    </tr>
  </tbody>
</table>

