# PracticaMarkdown
## H2 Example
### H3 Example


Emphasis:
this is an *italic* example
this is a **bold** example
this is a ~~crossed~~ example


List:
- 1 Item 1
- 2 Item 2
    - Subitem 2.1
        - Subitem 2.1.1

Ordered list:
1. First
2. Second


Link:
[Link](https://example.com)

Image:
![Alt](https://placehold.co/400)


Quote:
> This is a quote


Code inline:
`System.out.println("Hello World");`

Block code:
```java
public class Hola {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```


Table:
| Name | Age | City |
|:-------|----:|:----------|
| Ana | 25 | Granada |
| Juan | 30 | Jaén |

> [!NOTE]
> Text align: :--- left, ---: right, :---: center


Todo list:
- [x] Task 1
- [x] Task 2
- [ ] Task 3
- [ ] Task 4


Alerts:
- Note: 
> [!NOTE]
> To show information.
- Tip:
> [!TIP]
> To show advices
- Warning: 
> [!WARNING]
> To show must do or must not do info


Footnotes:
This is an easy example of a footnote[^1].
[^1] Here is the detailed explanation of the footnote.


Accordion:

<details>
<summary>Accordion example</summary>
- You can put html tags as **details**
- In the summary tag you put the accordion description
</details>


Flowchart example:
```mermaid
flowchart LR
    A[Web Browser] -->|HTTP Request| B[App Server]
    B --> C[PHP Backend]
    B --> D[Java Backend]
    D --> E[(Database)]
    C --> E[(DataBase)]
```


Image from other project location:
Image:
![Alt](images/phplogo.jpeg)


Link to other file from the project:
[Link to Changelog](CHANGELOG.md)
