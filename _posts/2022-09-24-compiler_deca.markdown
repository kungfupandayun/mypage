---
layout: post
title:  "Compiler for a programming language"
categories: projects
---

In this project, we have built a compiler for a programming language under Java named Deca. This compiler is built under 3 main pilers, lexicographical and syntax analysis, Semantic analysis and Intermediate code generator. <a href="https://www.guru99.com/compiler-design-phases-of-compiler.html#"> (Compiler phases Explaination)</a> In summary, it first identifies the lexical units (token) in the source code such as identifier, mathematical operators or any predefined constant. Next, it analyses syntaxically correct of an expression and start to construct the expression into a tree. After this, it checks if a statement is semantically correct. (Correctly typed, declared variables ...) And the end, generate assembly codes according to the tree constructed.
<a href="\assets\images\compiler_classes_design.png">
    <center>
        <img 
            src="\assets\images\compiler_classes_design.png" 
            alt="Tree expression"
        >
    </center>
</a>

