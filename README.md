# Exp-3-Create-a-Web-Layout-using-FLEXBOX
# HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Flexbox Web Layout</title>
</head>
<body>

    <header>
        <h1>Exp-3 Create a Web-Layout using FLEXBOX</h1>
    </header>

    <div class="container">
        <aside class="sidebar">
            <h2>Sidebar 1</h2>

        </aside>

        <main>
            <h2>Main Content</h2>
        </main>

        <aside class="sidebar">
            <h2>Sidebar 2</h2>
        </aside>
    </div>

    <footer>
        <p>AKASH A 212221040010</p>
    </footer>

</body>
</html>

```
# CSS
```
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    display: flex;
    height: 560px;
}

header, footer, aside, main {
    padding: 20px;
}

header, footer {
    background-color: #000000;
    color: #fff;
    text-align: center;
}

header h1, footer p {
    margin: 0;
}

.sidebar {
    flex: 1;
    background-color: #f0f0f0;
}

main {
    flex: 2;
    background-color: #fff;
    
}
main h1{
    display: flex;
    align-items: center;
    justify-content: center;
}

footer {
    background-color: #000000;
    color: #fff;
    text-align: center;
}

```
#Output
![Screenshot (76)](https://github.com/21002624/Exp-3-Create-a-Web-Layout-using-FLEXBOX/assets/113762183/b3119eb5-ea1b-48b8-90ab-c5e95622c00a)
