---
title: Vim es amor 
author: Sebastian Velasco (twitch.tv/velas_code) 
date: 2021-03-07
---

# Quien es este man?

Holi 👋

Front End Developer, aprendiendo Back, proyectos de todo tipo.

Como todos: aprendiendo todo el tiempo.

# Redes Sociales

Pueden escribirme, con gusto respondo.
- [Twitch: velas_code](twitch.tv/velas_code)
- [Instagram: velas_code](instagram.com/velas_code)
- [Github: sebasvelasco353](github.com/sebasvelasco353)

---

# pero antes de la charla, que es eso?
- **Una herramienta**
- vi -> vim -> neoVim
- Editor de texto que nace en 1991 (somos de la misma generacion).
- Desarrollado por Bram Moolenaar.
- Presente en Unix y por eso mismo en la mayoria de servidores.

---

# VIM vs NVIM

```
                                                                           
           ,::::::~y: ::::::,                        `       `             
          ,7++++^+BN%R=^++++c^                      ~{,      z~            
          'f=~~~^j@QQQt;~~~;w;                     !yj7`     nk;           
           `I~~~|@QQQQ^~~~!6!                    `*aaytL`    {A6|          
           `I~~~|@QQ#;~~~^q~                     :IyayYY^    uqqq~         
           `I~~~|@Qb~~~~*Q!                      ~Ynayuuu~   {KKK;         
           ;I~~~|@k_~~~LQQD~                     ~uuj5}}fn'  fbdd;         
          >kx~~~|c~~~~}@QQQg?                    ~ff}L7jjjJ` jDDD;         
         ;RQx~~~=~~~;y@QQQQQQ;                   ~jjj*'fjjj| jRRR;         
          |@x~~~~~~iw@QQQQQ@L                    ~jyy* ~yyyy^y%%%;         
           +I~~~~~!WbQQQQQ@^                     ~yyy?  <555y6ggg!         
           `I~~~~=QEQQXQqQo|;                    ;ooa|   7aaaKW88!         
           `I~~~*QQ?@KyR^Jn*;                    ;ZZZL   .ySSb%NN!         
           `I~~z@Qjd@?@QT,jj                     '5mmL    ,mwb%gR,         
           `{^{{I@*@QyXXd^tX                      'jwL     ^EDgA,          
            ,^~  ^@Q@> `` ``                       `zL      \Do`           
                  ~Q;                               `~      `i`            
                                                                           

```

---

# competencia o amigos?

- NeoVim es un fork de Vim enfocado en expansion y modificacion.
- Vim es mantenido por su creador con ayuda de la comunidad, NeoVim es mantenido por la comunidad.
- la mayoria de nuevas funcionalidades (por ejemplo async) llegan primero a Neovim y despues son implementadas por Vim.

## Pero entonces, cual?
Es una herramienta entonces la respuesta es: el que prefieras... o ninguno.

---

# Es cuestion de practica y amor. 

Vim es como el amor de un perrito, hay que cuidarlo y poner de nuestra parte, cuando se crea la
relacion no vas a querer dejarlo.

Ademas, si quieres que haga cosas te toca entrenarlo.

```

     |\_/|                  
     | @ @   Woof! 
     |   <>              _  
     |  _/\------____ ((| |))
     |               `--' |   
 ____|_       ___|   |___.' 
/_/_____/____/_______|

```

---

# Pero... para que?

Si ya tengo VSCode o Sublime porque voy a perder mi tiempo con Vim? eso no es de los 90s? ok BOOMER!

---
- Configuraciones.
- Divertido y retador.
- Comodidad.
- Esta en todos los unix systems.
- Nerd points.

---

# Vim es una herramienta mas.

y como toda herramienta lo importante es sentirte a gusto usandola.

X o Y teclado no te hacen mejor desarrollador o desarrolladora, pero ayudan a moverte de forma mas
comoda, lo cual se refleja en mejor codigo u horas mas amenas mientras trabajas, pasa lo mismo con Vim.

---

# "Vim is not an editor, its an instrument"
BeginBot - sep 6, 2020

lo dijo en [esta presentacion](https://www.youtube.com/watch?v=EJqnWXDJZr0&t=343s&ab_channel=Beginbot)
y les recomiendo que si les gusta el tema de vim y la programacion vean sus videos, el sabe mucho mas que yo.

---

# Modos
Vim tiene diferentes modos de trabajo, al principio puede parecer raro pero una vez te acostumbras a usarlos
te das cuenta que te ayudan a moverte y modificar el codigo mas facilmente.

- **Insert:** como lo dice el nombre, es el modo en el que te permite insertar texto como lo harias en un editor como vs code,
lo activas presionando i
- **Normal:** es el modo en el que mas pasas tiempo, es con el cual te mueves, copias, pegas y reemplazas cosas sin escribir, ingresas
a este modo presionando esc o saliendo del modo en el que te encuentres.
- **Visual:** en este modo seleccionas texto y puedes eliminarlo, copiarlo o cortarlo, ingresas presionando v.
- **Visual-Block:** Es para seleccionar en bloque, se va a generar un rectangulo desde donde empezaste la seleccion hasta donde tengas el cursor,
ingresas a este modo presionando control - v.

---

# Comandos y mappings!
Son el alma, corazon y motor de vim, la razon por la que nos gusta y lo que probablemente modifiquemos mas.

- SALIR -> :q
- Guardar -> :w
- :h cosa -> el manual sobre cosa
- Ir a la linea N -> :n
- Cambiar al Buffer n -> :bn
- Movimiento -> hjkl

```vim

" Esto es un ejemplo de como puedo hacer mappings
nnoremap <leader>udt :undotreetoggle<cr>
nnoremap <UP> :echo 'NO USAR LAS ARROW KEYS!'<cr>

```

---

# map vs noremap
- map es recursivo.
- noremap es no recursivo.

```vim
:map u $  <-- final de la linea
:map r u  <-- ejecuta u, osea que es el final de la linea
:noremap s r <-- va a ejecutar un replace, es decir el comando original de la r
```

---

# ColorSchemes

- Vim tiene muchos integrados y miles por descubrir.
- posibilidad de crear nuevos como guste [por ejemplo usando esto](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim)


# Plugins
Vim y NeoVim tienen un ecosistema de plugins muy extenso y que esta en constante crecimiento, si necesitas haceer algo es muy probable
que encuentres un plugin que te ayude a hacerlo, si es que no hay una forma de hacerlo nativo en vim.

Mi configuracion de vim la encuentran en [mis dotfiles](https://github.com/sebasvelasco353/.dotfiles), este repo esta en constante
desarrollo asi que si tienen alguna pregunta con gusto lo respondo.

---

# Conclusion

- Es una herramienta, no una solucion.
- requiere esfuerzo.
- vale la pena.
- tiene mucha experimentacion, esta bien si algunas veces nos tiramos las cosas.
- Una comunidad abierta y dispuesta a ayudar.

---

# Muchas gracias!
Algunos lugares donde encuentran buena informacion sobre vim:

- [ThePrimeagen](https://www.youtube.com/channel/UC8ENHE5xdFSwx71u3fDH5Xw)
- [BeginBot](https://www.youtube.com/channel/UC-VnbnvbOn2vS8SI6S2GqKA)
- [Ben Awad - vim tutorial](https://www.youtube.com/watch?v=IiwGbcd8S7I)
- [Hola Mundo (excelente contenido)](https://www.youtube.com/watch?v=EYaPvgXjFXo)
- [tambien de Hola Mundo](https://www.youtube.com/watch?v=ST-PZ9VcU7g) 
- vimtutor en la consola
- :h en vim
