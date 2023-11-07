### Hi there 👋


    ---
    header-includes:
        - \usepackage{multicol}
        - \newcommand{\hideFromPandoc}[1]{#1}
        - \hideFromPandoc{
            \let\Begin\begin
            \let\End\end
          }
    ---
    
    # Rule 1
    Description for rule 1.
    
    \Begin{multicols}{2}
    ## Good
    ```c
    int foo (void) 
    {
        int i;
    }
    ```
    
    ## Bad
    ```c
    int foo (void) {
        int i;
    }
    ```
    \End{multicols}

<!--
**RDaniel396/Rdaniel396** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
