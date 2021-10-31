---
title: My First MarkDown
author: Echo Pan
date: 2021-10-31
category: Jekyll
layout: post
---

## 标题

```markdown
# 一级标题 {#my_id}
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

# 一级标题 {#my_id}

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

***
💚注：设置`.class`是MPE的特性，GitHub暂不支持  

***

## 正文

正文直接输入即可  

## 换行

换行：在行尾空两行  
隔行换行：空一行即可

💚注：隔行相当于切换段落，行尾换行则仍在同一段落内

## 代码块

一对```可以插入代码块，不同语言在第一行末尾加上语言名称可以显示不同类型的语法高亮

代码块支持语言：`1c`, `abnf`, `accesslog`, `actionscript`, `ada`, `apache`, `applescript`, `arduino`, `armasm`, `asciidoc`, `aspectj`, `autohotkey`, `autoit`, `avrasm`, `awk`, `axapta`, `bash`, `basic`, `bnf`, `brainfuck`, `cal`, `capnproto`, `ceylon`, `clean`, `clojure`, `clojure-repl`, `cmake`, `coffeescript`, `coq`, `cos`, `cpp`, `crmsh`, `crystal`, `cs`, `csp`, `css`, `d`, `dart`, `delphi`, `diff`, `django`, `dns`, `dockerfile`, `dos`, `dsconfig`, `dts`, `dust`, `ebnf`, `elixir`, `elm`, `erb`, `erlang`, `erlang-repl`, `excel`, `fix`, `flix`, `fortran`, `fsharp`, `gams`, `gauss`, `gcode`, `gherkin`, `glsl`, `go`, `golo`, `gradle`, `groovy`, `haml`, `handlebars`, `haskell`, `haxe`, `hsp`, `htmlbars`, `http`, `hy`, `inform7`, `ini`, `irpf90`, `java`, `javascript`, `json`, `julia`, `kotlin`, `lasso`, `ldif`, `leaf`, `less`, `lisp`, `livecodeserver`, `livescript`, `llvm`, `lsl`, `lua`, `makefile`, `markdown`, `mathematica`, `matlab`, `maxima`, `mel`, `mercury`, `mipsasm`, `mizar`, `mojolicious`, `monkey`, `moonscript`, `n1ql`, `nginx`, `nimrod`, `nix`, `nsis`, `objectivec`, `ocaml`, `openscad`, `oxygene`, `parser3`, `perl`, `pf`, `php`, `pony`, `powershell`, `processing`, `profile`, `prolog`, `protobuf`, `puppet`, `purebasic`, `python`, `q`, `qml`, `r`, `rib`, `roboconf`, `rsl`, `ruby`, `ruleslanguage`, `rust`, `scala`, `scheme`, `scilab`, `scss`, `smali`, `smalltalk`, `sml`, `sqf`, `sql`, `stan`, `stata`, `step21`, `stylus`, `subunit`, `swift`, `taggerscript`, `tap`, `tcl`, `tex`, `thrift`, `tp`, `twig`, `typescript`, `vala`, `vbnet`, `vbscript`, `vbscript-html`, `verilog`, `vhdl`, `vim`, `x86asm`, `xl`, `xml`, `xquery`, `yaml`, `zephir`

```java
//Java代码块
Public class Test{
    public static void main(String[] args){
       String[] arr={"beijing","shanghai","shenzhen"};
       for(String x:arr){
       System.out.println(x);
      }
    }
}
```

```js
//JS代码块
var div=document.getElementsByTagName("div");
div[0].onclick=function(){
  alert("Hello World!");
};
```
    //缩进四个空格，以代码块形式呈现内容
    $var=hello;
    echo "$var world!";

## 行内代码

正文代码通过一对双反引号进行输出，比如``echo "Hello World";``

## 有序列表

格式：数字+点+空格，使用``Tab``键添加子列表

1. 星期一
2. 星期二
3. 星期三
   1. 早上
   2. 中午
   3. 晚上

## 无序列表

格式：短横杠+空格

- 1月
  - 1号
  - 2号
- 2月
  - 27号
  - 28号
    - 早上
    - 晚上

## 加粗和倾斜

一对``*``，*倾斜*  
一对``**``，**加粗**  
一对``***``，***加粗和倾斜***

💚注：双下划线也能实现相同的效果

## 图片和链接

### 图片

```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### 超链接

1. ``<https://github.com>``  
  a. <https://github.com>  
2. ``[GitHub](https://github.com)``  
  a. [GitHub](https://github.com)

## 引用

马尔克斯在《百年孤独》的开头这样写道：  

> Muchos años después, frente al pelotón de fusilamiento, el coronel Aureliano Buendía había de
recordar aquella tarde remota en que su padre lo llevó a conocer el hielo.  

> 多年以后，面对行刑队，奥雷里亚诺·布恩迪亚上校将会回想起父亲带他去见识冰块的那个遥远的下午。

## 分割线

- 横杠 x 3 ``---``  
- 星号 x 3 ``***``  
- 下划线 x 3 ``___``  

💚注：不要在同一段落内使用（隔行使用！）

---

***
___

## 任务列表

```markdown
- [x] 背10个英语单词
- [x] 看一部电影
- [x] 阅读15分钟
- [ ] 跑步3公里
- [ ] 购物
```

- [x] 背10个英语单词
- [x] 看一部电影
- [x] 阅读15分钟
- [ ] 跑步3公里
- [ ] 购物

## 表格

```markdown
姓名 | 爱好
--- | ---    //短横杠区分表格首行
菲菲 | 阅读
唐海 | 打羽毛球
千月 | 唱歌
```

姓名 | 爱好
--- | ---
菲菲 | 阅读
唐海 | 打羽毛球
千月 | 唱歌

## 用户名

通过@来提及某人或某组织，比如 @echopan

## 删除线

一对双波浪可以实现删除线效果  

``~~delete~~``，~~删除~~