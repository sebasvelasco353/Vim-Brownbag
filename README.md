---
title: Vim es amor 
author: Sebastian Velasco (twitch.tv/velas_code) 
date: 2021-02-13
extensions: []
styles: {} 
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
- **_Una herramienta_**
- Editor de texto que nace en 1991 (somos de la misma generacion).
- Desarrollado por Bram Moolenaar.
- Presente en Unix.

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

- NeoVim es un fork de Vim enfocado en posibilidades de expansion.
- Vim es mantenido por su creador con ayuda de la comunidad, NeoVim es mantenido por la comunidad.
- la mayoria de nuevas funcionalidades (por ejemplo async) llegan primero a Neovim y despues son implementadas por Vim.

## Pero entonces, cual?
Es una herramienta entonces la respuesta es: el que prefieras... o ninguno.

---

# Vim Es Amor


Vim es como el amor de un perrito, hay que cuidarlo y poner de nuestra parte, cuando se crea la
relacion no vas a querer dejarlo.

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
# La respuesta es:
- Configuraciones
- Divertido y retador
- Comodidad
- esta en todos los servidores
- hipster

---

# Vim es una herramienta mas.

y como toda herramienta lo importante es sentirte a gusto usandola.

X o Y teclado no te hacen mejor desarrollador o desarrolladora, pero ayudan a moverte de forma mas
comoda, lo cual se refleja en mejor codigo u horas mas amenas mientras trabajas, pasa lo mismo con Vim.

---

# "Vim is not an editor, its an instrument"
BeginBot - sep 6, 2020

lo dijo en [esta presentacion](https://www.youtube.com/watch?v=EJqnWXDJZr0&t=343s&ab_channel=Beginbot),
y les recomiendo que si les gusta el tema de vim y la programacion vean sus videos, el sabe mucho mas que yo.

---

# Comandos y mappings!
Son el alma, corazon y motor de vim, la razon por la que nos gusta y lo que probablemente modifiquemos mas.

- SALIR -> :q
- Guardar -> :w
- Ir a la linea N -> :n
- Cambiar al Buffer n -> :bn

```vim

" Esto es un ejemplo de como puedo hacer mappings
nnoremap <leader>udt :undotreetoggle<cr>
nnoremap <UP> :echo 'NO USAR LAS ARROW KEYS!'<cr>

```

---

# ColorSchemes

- Vim tiene muchos integrados y miles por descubrir.
- posibilidad de crear nuevos como guste [por ejemplo usando esto](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim)
