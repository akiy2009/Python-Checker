# Python-Checker
## ENGLISH  
This program automatically checks the Python code submitted in a Pull Request using GitHub Actions.  

### SET UP
[Setting]>>[General]>>[Action]>>[General]>>[Workflow permissins]>>[Read and write permissins]

### ERROR CODE LIST
[E101]	Mixed indentation (tabs and spaces)  
[E111]	Incorrect indentation  
[E114]	Incorrect indentation in a comment  
[E117]	Incorrect indentation inside a comment  
[E201]	Unnecessary space after () or []  
[E202]	Unnecessary space before () or []  
[E203]	Space before : (violates PEP8)  
[E211]	Unnecessary space before a function argument list  
[E225]	Missing space around an operator  
[E226]	Improper spacing around specific operators (*, /, +, -, etc.)  
[E231]	Missing space after ,  
[E241]	Multiple spaces before a comma in a list or dictionary  
[E301]	No blank line before a class definition  
[E302]	Expected 2 blank lines before a function, but found only 1  
[E303]	Too many blank lines  
[E305]	No blank line after a function or class definition  
[E401]	Multiple import statements on a single line  
[E402]	import statement not at the top of the file  
[E501]	Line too long (default is 79 characters, configurable)  
[F401]	Unused import statement  
[F403]	from module import * is discouraged  
[F405]	Using import * may cause undefined names  
[F821]	Using an undefined variable  
[F841]	Variable is defined but not used  
[C901]	Function is too complex (default threshold is 10)  
[D100]	Missing docstring in a module  
[D101]  Missing docstring in a class  
[D102]	Missing docstring in a function  
[E722]	Use except Exception: instead of a bare except:  
[E741]	Avoid single-letter variable names (e.g., l, O, I)  
[W291]	Trailing whitespace  
[W293]	Whitespace on an empty line  

#### create by akiy2009

## 日本語 
このプログラムでは、Pull Request（プルリクエスト） で送信された Python コードを GitHub Actions を通して自動的にチェックします。  

### セットアップ
[Setting]>>[General]>>[Action]>>[General]>>[Workflow permissins]>>[Read and write permissins]

### エラーコード一覧  
[E101]	インデントが混在（タブとスペース)  
[E111]	インデントが間違っている  
[E114]	コメントのインデントが間違っている  
[E117]	コメント内のインデントが間違っている  
[E201]	() や [] の直後に不要なスペースがある  
[E202]	() や [] の直前に不要なスペースがある  
[E203]	: の前にスペースがある（PEP8 違反）  
[E211]	関数の引数リストの直前に不要な空白がある  
[E225]	演算子の前後にスペースがない  
[E226]	特定の演算子（*, /, +, - など）の前後に適切なスペースがない  
[E231]	, の直後にスペースがない  
[E241]	リストや辞書でカンマの前に複数のスペースがある  
[E301]	クラスの定義の前に空行がない  
[E302]	関数の前に空行が 2 つ必要（見つかったのは 1 つ）  
[E303]	余分な空行がある  
[E305]	関数やクラスの後に空行がない  
[E401]	1 行に複数の import 文がある  
[E402]	import 文がファイルの先頭以外にある  
[E501]	行が長すぎる（デフォルト 79 文字、変更可）  
[F401]	未使用の import がある  
[F403]	from module import * は非推奨  
[F405]	import * を使用した場合、未定義の名前が使用される可能性がある  
[F821]	未定義の変数を使用  
[F841]	変数が定義されているが使用されていない  
[C901]	関数の複雑度が高すぎる（デフォルトは 10）  
[D100]	モジュールに Docstring がない  
[D101]	クラスに Docstring がない  
[D102]	関数に Docstring がない  
[E722]	except: ではなく except Exception: を使用するべき  
[E741]	1 文字の変数名（例: l, O, I）は避けるべき  
[W291]	行末にスペースがある  
[W293]	空行にスペースがある  

#### created by akiy2009
