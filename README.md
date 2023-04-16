# TINY-compiler-Compiler_Construction_Principles_and_Practice
## from homework Compiler Construction: Principles and Practice by Kenneth C. Louden
### NIS2336-编译原理-上海交通大学 2023/4/16 @zeroking.sjtu.edu.cn
目标：在了解TINY language语言的基础上，使用C/C++语言编程实现词法分析，根据程序段模拟自动机的分析过程生成token序列。

[TINY language语言的词法单元](https://blog.csdn.net/qq_41112170/article/details/106891811?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522168163309216800215052342%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=168163309216800215052342&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-1-106891811-null-null.142^v83^insert_down38,239^v2^insert_chatgpt&utm_term=TINY%20language%E8%AF%AD%E8%A8%80%E7%9A%84%E8%AF%8D%E6%B3%95%E5%8D%95%E5%85%83&spm=1018.2226.3001.4187)

文件global.h中定义了所有的词法单元类型TokenType，并在lexer.h中声明。本次实验要求在读懂lexer.c中已有代码的基础上完善补全lexer.c中的主函数getToken(void)，该函数通过判断当前状态并根据当前读入的词法单元来输出当前读入词法单元的token，并更新状态和词法单元，根据给出代码中的示例补全switch语句中case为其他状态时的情况。

给定一段符合TINY language语法的代码，写成.tny文件，放在build\test文件夹内。要求程序能够输出这段代码的每一行，在每一行的后面输出这一行所有词法单元的token。

示例输出见out_example文件。
