| Nom                | Syntaxe                   | Effet                                     | Remarques                                                      |
|--------------------|---------------------------|-------------------------------------------|----------------------------------------------------------------|
| Heading (h1)       | # [texte]                 | Crée un heading de niveau h1 pour [texte] |                                                                |
| Heading (h2)       | ## [texte]                | Crée un heading de niveau h2 pour [texte] |                                                                |
| Heading (h3-h6)    | ###-######                | Crée un heading de niveau h3 à h6         |                                                                |
| Heading (h1) (alt) | [texte]   
=======           | Crée un heading de niveau h1 pour [texte] | Une autre méthode pour créer un heading                        |
| Heading (h2) (alt) | [texte]   
-------           | Crée un heading de niveau h2 pour [texte] | Une autre méthode pour créer un heading                        |
| Bold               | \*\*[texte]\*\*           | Affiche [texte] en gras                   |                                                                |
| Bold (alt)         | \_\_[texte]\_\_           | Affiche [texte] en gras                   | Une autre méthode                                              |
| Italic             | \*[texte]\*               | Affiche [texte] en italique               |                                                                |
| Italic (alt)       | \_[texte]\_               | Affiche [texte] en italique               | Une autre méthode                                              |
| Bold & Italic      | \*\*\*[texte]\*\*\*       | Affiche [texte] en gras et en italique    |                                                                |
| Bold & Italic      | \_\_\_[texte]\_\_\_       | Affiche [texte] en gras et en italique    | Il est également possible de combiner les deux méthodes        |
| Links              | \[texte](URL)              | Affiche [texte] en tant que lien vers URL |                                                                |
| Images             | \![alt]\(image.jpg "titre") | Affiche image.jpg avec un titre et un alt | Il est évidemment possible de combiner une image et un lien... |

> Headings | # times the heading wanted
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5

---


> Bold text | ** text **

**bold text**  


> Italic | * text *  

*italic text*

> Bold and italic | _** text ** _

_**bold and italic**_

> Striketrough | ~~ text ~~

~~Striketrhough~~

> Unordered list | * item

* item 1
* item 2
* item 3
    * nested item

> Ordered list

1. Item 1
1. Item 2
1. Item 3
    1. Item 3a

> Horizontal rule | ---

---

> Links [ name of link] ( Url of link)

[Wikipedia](https://www.wikipedia.org/)

> Images ![name of image](url of image)

![Insect](https://homepages.cae.wisc.edu/~ece533/images/monarch.png)

---
# GitHub markdown

> code blocks |


```javascript
    function helloWorld(){
    let a = "Hello World !";
    console.log(a);
}
```

![animated gif](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)
