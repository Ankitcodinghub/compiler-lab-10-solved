# compiler-lab-10-solved
**TO GET THIS SOLUTION VISIT:** [Compiler Lab 10 Solved](https://www.ankitcodinghub.com/product/compiler-lab-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91902&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Compiler Lab 10 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Lab Assignment 10

Intermediate representation(s)/ generating Intermediate representation(s)

Q1 [AST]. There are various intermediate representations such as Abstract-Syntax-Tree (AST), Directed-acyclic-graph (DAG), and 3-address code. Consider your expression grammar from assignment 9 with operations such as addition, subtraction, multiplication and division.

<ol>
<li>Using semantic actions, design S-attributed/L-attributed translation grammar to generate AST. Explain all the semantic actions that you considered. Submit a document with brief explanations.</li>
<li>Implement your solution (NOTE: We had discussed about combining evaluation of semantic actions with top-down/bottom-up parsing). Your program should take an expression as input and generate its corresponding AST as output (you may decide about how you present/ store the output).</li>
</ol>
Q2 [3-address code]. There are various intermediate representations such as Abstract-Syntax-Tree (AST), Directed-acyclic-graph (DAG), and 3-address code. Consider your expression grammar from assignment 9 with operations such as addition, subtraction, multiplication and division.

<ol>
<li>Using semantic actions, design S-attributed/L-attributed translation grammar to generate -3-address code. Explain all the semantic actions that you considered. Submit a document with brief explanations.</li>
<li>Implement your solution (NOTE: We had discussed about combining evaluation of semantic actions with top-down/bottom-up parsing). Your program should take an expression as input and generate its corresponding 3-address code as output.</li>
</ol>
Q3 [DAG- OPTIONAL]. Semantic actions for generating DAG for the above problem. The output should be DAG of the input expression in a readable form.

Q4 [OPTIONAL]. GCC intermediate codes:

You may explore the internals, and understand the intermediate representations used by gcc.

Produce internal representations for some simple programs (program with few simple basic statements, program with 1 for loop etc), observe some of the intermediate representations generated by gcc for the considered programs.

The GCC compiler uses three intermediate representations:

<ol start="3">
<li>GENERIC: language independent tree representation of the entire function</li>
<li>GIMPLE: three-address representation generated from GENERIC</li>
<li>RTL: low-level representation known as register transfer language</li>
</ol>
gcc produces the textual forms of the following intermediate representations of a program being compiled:

<ol>
<li>Abstract Syntax Tree (AST). The -fdump-tree-original-raw switch dumps the textual representation of the AST for given input source.</li>
<li>Gnu SIMPLE representation (GIMPLE). The -fdump-tree-gimple-raw switch dumps the GIMPLE representation of the input source (more readable form without -raw).</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>Control Flow Graph (CFG). The -fdump-tree-cfg-raw switch dumps the CFG form of the GIMPLE code.</li>
<li>Register Transfer Language (RTL IR). The -da switch dumps the RTL IR of the input source program with the pass number as a part of the dump file name.</li>
</ol>
</div>
</div>
</div>
