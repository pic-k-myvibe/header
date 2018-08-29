# Instrucciones

## Esta vista es la del resultado del formulario.

Pueden descargar el repositorio completo o simplemente agregar el header y footer.

### Header

#### HTML
```
<header>
  <nav>
    <div class="menu">
      <div class="menu-izq">
        <ul>
          <li><a href="#"><img src="https://www.logolynx.com/images/logolynx/50/50e3428738c12cc2ad7ce3d06e2820f5.png" alt=""></a></li>
          <li><a href="#">Lugares</a></li>
          <li><a href="#">Experiencias</a></li>
        </ul>
      </div>
      <div class="menu-der">
        <ul>
          <li class="menu-search">
            <input class="search" type="search" name="" value="" placeholder="Buscar">
          </li>
          <li class="box-icon-user">
            <img class="icon-user" src="img\icon-user.png" alt="perfil">
            <a href="#">Perfil</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</header>
```

#### CSS
```
/*--- header ---*/
.menu {
  width: 100%;
  background-color: #4fd4be;
  display: flex;
  justify-content: space-between;
  position: fixed;
  top: 0;
  box-shadow: 0 0.5rem 1rem rgba(97, 93, 93, 0.15);
}
.menu a {
  text-decoration: none;
  color: #fff;
}
.menu-izq {
  display: flex;
  align-items: center;
}
.menu-izq ul,
.menu-der ul {
  max-width: 500px;
  width: 100%;
  display: flex;
  list-style: none;
  margin: 0;
  padding: 5px 0;
}
.menu-izq ul li,
.menu-der ul li {
  margin: 0 10px;
}
.menu-izq ul li {
  margin: 0 20px;
  display: flex;
  align-items: center;
}
.menu-izq img {
  width: 37px;
}
.box-icon-user {
  display: flex;
  justify-content: center;
  align-items: center;
}
.icon-user {
  width: 37px;
  height: auto;
  margin-right: 5px;
}
.menu-search {
  display: flex;
  align-items: center;
}
.search {
  padding: 8px 16px;
  border-radius: 4px;
  border-color: transparent;
}
```

### Footer

#### HTML
```
<footer>
  <div class="box">
    <p>Pickmyby© 2018</p>
    <div>
      <a href="#"><img src="img/facebook-logo-en-boton-circular-esbozado-de-social-simbolo.png" alt=""></a>
      <a href="#"><img src="img/twitter-boton-circular.png" alt=""></a>
      <a href="#"><img src="img/youtube.png" alt=""></a>
    </div>
    <p>Contactanos</p>
  </div>
</footer>
```

#### CSS
```
/*--- footer ---*/
footer {
  background-color: #3ca593;
  padding: 20px;
}
footer .box {
  display: flex;
  justify-content: space-between;
}
footer .box img {
  width: 37px;
  height: auto;
  margin-left: 10px;
}
```

Nota: Las imagenes las encuentran en la carpeta de img.