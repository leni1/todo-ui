<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="All product categories available on our site">
    <!-- TODO: Dynamically fill -->
    <title>Todos in this Category</title>
</head>
<body>
  <header>
    <h1 class="cat-header">All Todos in this Category</h1>
  </header> 
  <main class="cat-main">
    <h2 class="categories"><a href="#">Clean</a></h2>
    <h2 class="categories"><a href="#">Wash</a></h2>
    <h2 class="categories"><a href="#">Sleep</a></h2>
  </main>
</body>
</html>

<style>
:root {
  --black: #272722;
  --grey: #cacaca;
  --white: #fff;
}


html {
  box-sizing: border-box;
  font-family: "Noto Sans", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  color: var(--black);
  background-color: var(--grey);
}

*,
*:before,
*:after {
  box-sizing: inherit;
}

/* categories page */
.cat-header {
  display: grid;
  align-items: center;
  justify-content: center;
  font-weight: 500;
}

.cat-main {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
}

.categories {
  display: grid;
  justify-content: center;
  align-items: center;
  border: 5px solid rgba(0, 0, 0, 0.03);
  border-radius: 3px;
  font-size: 25px;
  font-weight: 400;
  background-color: var(--white);
  margin: 0px;
  padding: 20px;
}

.categories a {
  text-decoration: none;
}
</style>