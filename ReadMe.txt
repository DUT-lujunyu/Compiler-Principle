=======================================================================
文件说明：
① Compiler0.2.4/source文件夹：
	存放着需要进行编译的代码，其中“test.txt”为正常运行的文件，“ex-y.txt”为错误文件，错误类型为x类型下的第y种。（x：1：词法分析，2：语法分析，3：语义分析）具体的错误类型请查看“错误信息”文件夹。
②  Compiler0.2.4/runtime文件夹：
	存放程序执行过程中生成的中间结果文件，以及运行中需要调用的exe文件。
③ 错误信息文件夹：存放着三种类型的错误信息对照表
=======================================================================
运行准备：
①将需要编译的文件存放在Build V4/source文件夹中。
②运行时生成的中间文件可以到Build V4/runtime文件夹中查看。
③不要动Build V4/runtime文件夹下的compile.exe，那是C++文件生成的可执行文件
=======================================================================
程序使用说明：
①运行时请在文字输入栏里输入想要打开的文件名字（包括后缀.txt），并确保该文件在source文件夹下。
②点击左侧的InputOriginalFile即可导入源文件并进行编译。
③点击右侧的CompilingMessage可以显示编译的信息（报错等）。
④点击LexicalAnalysis显示词法分析结果。
⑤点击SemanticAnalysis显示语义分析结果。
⑥点击ExcuteResult显示解释程序执行过程，以及运行结果。