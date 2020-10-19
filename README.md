#### markdown editor list

|                     |        [joplin](https://joplinapp.org/)        |         typora.io          | hackmd.io |      [Inkdrop](https://www.inkdrop.app/)       |  stackedit.io   | [vscode](https://code.visualstudio.com/download) |                  [notion](notion.so)                   |
|:-------------------:|:----------------------------------------------:|:--------------------------:|:---------:|:----------------------------------------------:|:---------------:|:------------------------------------------------:|:------------------------------------------------------:|
|     mermaid.js      |                       ✔                        |             ✔              |     ✔     |                       ❌                       |        ✔        |                        🤔                        |                           ❌                           |
|       MathJax       |                       ✔                        |             ✔              |     ✔     |                       ❌                       |      Katex      |                        ✔                         |                           ❌                           |
|    flowchart.js     |                       ❌                       |             ✔              |     ✔     |                       ❌                       |        ✔        |                        🤔                        |                           ❌                           |
|       abc.js        |                       ❌                       |             ❌             |     ✔     |                       ❌                       |        ✔        |                        🤔                        |                           ❌                           |
|       search        |                       ✔                        |             ✔              |    ❌     |                       ✔                        |       ❌        |                        ✔                         |                           ✔                            |
|        find         |                       ✔                        |             ✔              |     ✔     |                       ✔                        |        ✔        |                        ✔                         |                           ✔                            |
|    search by tag    |                       ✔                        |             ✔              |     ✔     |                       ✔                        |       ❌        |                        ✔                         |                           ✔                            |
|       folder        |                       ✔                        |             ✔              |    ❌     |                       ❌                       |        ✔        |                        ✔                         |                           ✔                            |
|   code highlight    |                       ✔                        |             ✔              |     ✔     |                       ✔                        |        ✔        |                        ✔                         |                           ✔                            |
|   embedding video   |                       ❌                       |             ❌             |     ✔     |                       ❌                       |        ✔        |                        🤔                        |                           ✔                            |
|        price        |                      free                      |            free            |   free    |                   demo free                    | has pro version |                       free                       |                                               free         | 
|     open source     |                      foss                      |             🤔             |   foss    |                       ❌                       |        ✔        |                        ✔                         |                    ✔                                    |
| Real-time rendering |                       ✔                        |             ❌             |     ✔     |                       ✔                        |        ✔        |                        ✔                         |                           ✔                            |
|    upload image     |                       ❌                       |             ❌             |     ✔     |                       ❌                       |        ✔        |                        🤔                        |                           ❌                           |
|    chrome plugin    |                       ❌                       |             ❌             |    ❌     |                       ❌                       |        ✔        |                        🤔                        |                           ✔                            |
|     auto format     |                       ❌                       |             ❌             |     ✔     |                       ❌                       |        ✔        |                        ✔                         |                           ✔                            |
|       iframe        |                       ❌                       |             ❌             |     ✔     |                       ❌                       |        ✔        |                        🤔                        |                           ✔                            |
|        TODO         |                       ✔                        |             ✔              |     ✔     |                       ✔                        |        ✔        |                        ✔                         |                           ✔                            |
|    visualization    |                       4                        |        like vscode         |     3     |                      4.5                       |        3        |                               🤔                   |                       4.5                                 |
|      platform       | ![][win]![][mac]![][linux]![][android]![][ios] | ![][win]![][mac]![][linux] | ![][web]  | ![][win]![][mac]![][linux]![][android]![][ios] |    ![][web]     |            ![][win]![][mac]![][linux]            | ![][win]![][mac]![][linux]![][android]![][ios]![][web] |
|    sync on cloud    |                       ❌                       |             ❌             |     ✔     |                       ❌                       |        ✔        |                        🤔                        |                           ✔                            |
|    edit and view    |                       ✔                        |             ❌             |     ✔     |                       ✔                        |        ✔        |                        🤔                        |                           ❌                           |



[mac]: https://cdn1.iconfinder.com/data/icons/system-black-circles/512/mac_os_X-20.png
[win]:https://cdn1.iconfinder.com/data/icons/system-black-circles/512/microsoft_windows-20.png
[linux]:https://cdn1.iconfinder.com/data/icons/system-black-circles/512/linux_tox-20.png
[ios]:https://cdn1.iconfinder.com/data/icons/system-black-circles/512/iOS-20.png
[android]:https://cdn1.iconfinder.com/data/icons/system-black-circles/512/android-20.png
[web]:https://cdn1.iconfinder.com/data/icons/system-black-circles/512/chrome_browser-20.png


---

## Component introduction

1. mermaid 
    1. [mermaid-js](https://github.com/mermaid-js/mermaid) [![Star on GitHub](https://img.shields.io/github/stars/mermaid-js/mermaid.svg?style=social)](https://github.com/mermaid-js/mermaid/stargazers)
    2. document: http://mermaid-js.github.io/mermaid/
    3. What diagrams you can draw.
        1. `Flowchart`
        2. `Sequence diagrams`
        3. `Class diagrams`
        4. `State diagrams`
        5. `Entity Relationship Diagrams`
        6. `User Journey Diagram`
        7. `Gantt`
        8. `Pie chart`
    4. Example
        1. ![](https://mermaid-js.github.io/mermaid/assets/img/header.png)
2. flowchart
    1. [flowchart.js](https://github.com/adrai/flowchart.js) [![Star on GitHub](https://img.shields.io/github/stars/adrai/flowchart.js.svg?style=social)](https://github.com/adrai/flowchart.js/stargazers)
    2. document [https://flowchart.js.org/](https://flowchart.js.org/)
    3. What diagrams you can draw
        1. FlowChart, but with a better line route, and a better 
    4. Example
        1. 
        ```
        st=>start: Start:>http://www.google.com[blank]
        e=>end:>http://www.google.com
        op1=>operation: My Operation
        sub1=>subroutine: My Subroutine
        cond=>condition: Yes
        or No?:>http://www.google.com
        io=>inputoutput: catch something...
        para=>parallel: parallel tasks

        st->op1->cond
        cond(yes)->io->e
        cond(no)->para
        para(path1, bottom)->sub1(right)->op1
        para(path2, top)->op1
        ```
        ![](https://raw.githubusercontent.com/adrai/flowchart.js/91999f6e7e9f9dbcbede61fcc4d9723a978465bd/imgs/example.svg)
3. abc
    1. [abc.js](https://github.com/paulrosen/abcjs) [![Star on GitHub](https://img.shields.io/github/stars/paulrosen/abcjs.svg?style=social)](https://github.com/paulrosen/abcjs.js/stargazers)
    2. document https://paulrosen.github.io/abcjs/
    3. You can write format code for specifying sheet music using only a string of characters
    4. Example
        1. 
        ```
        X: 1
        T: Cooley's
        M: 4/4
        L: 1/8
        K: Emin
        |:D2|EB{c}BA B2 EB|~B2 AB dBAG|FDAD BDAD|FDAD dAFD|
        EBBA B2 EB|B2 AB defg|afe^c dBAF|DEFD E2:|
        |:gf|eB B2 efge|eB B2 gedB|A2 FA DAFA|A2 FA defg|
        eB B2 eBgB|eB B2 defg|afe^c dBAF|DEFD E2:|
        ```
        ![](http://abcnotation.com/res/img/SpeedThePlough.png)
        
