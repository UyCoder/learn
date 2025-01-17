# 快捷代码

psvm    

```java
public static void main(String[] args) {
}
```

sout

```java
System.out.println();
```

"hello".sout

```java
System.out.println("hello");
```

```
Ctrl`+`Shift`+`Alt`+`N
```



常用的归纳

| 含义                                                         | idea-Mac                                                     | idea-Windows | eclipse-Mac                                                  | eclipse-Windows |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------------------------------------------------------ | --------------- |
| 根据类名搜索一个类(完全匹配)                                 | cmd  + O                                                     | ctrl+N       |                                                              |                 |
| 在当前文件跳转到指定行处                                     |                                                              | ctrl+G       |                                                              |                 |
| 方法参数提示显示                                             |                                                              | ctrl+P       |                                                              |                 |
| 格式化代码                                                   | cmd+alt+L                                                    | ctrl+alt+L   | cmd+shift+F                                                  |                 |
| 定位当前类的位置                                             | ![image-20191224201050517](images/image-20191224201050517.png) |              | ![image-20191126204442201](images/image-20191126204442201.png) |                 |
| 搜索包含此字符所有的东西                                     | cmd+shift+F                                                  | ctrl+shift+F |                                                              |                 |
| 根据类名搜索一个类(模糊匹配)                                 | shift 双击                                                   | shift 双击   |                                                              |                 |
| 可以看向上的继承关系，既能看继承关系，也能看实现了哪些接口   | cmd+alt+U                                                    |              |                                                              |                 |
| 可以看向上和向下的继承关系，只能看继承关系，不能看实现了哪些接口 | ctrl+H                                                       | ctrl + H     | cmd+T                                                        |                 |
| 光标上一次位置和下一次位置                                   |                                                              |              | cmd+alt+左右                                                 |                 |
| 智能补全声明                                                 | cmd+alt+V                                                    | ctrl+alt+V   |                                                              |                 |
| 补全代码                                                     | alt+/                                                        |              |                                                              | alt+ /          |
| 智能提示(实现未实现的接口，创建类....)                       | alt+Enter                                                    |              |                                                              |                 |
| 构造、Setter/Getter、toString、hashCode等                    | ctrl+return、cmd+n                                           | alt+insert   |                                                              |                 |
| 代码左右(上下)分屏                                           | 文件右键->Split Vertically(Horizontally)                     |              |                                                              |                 |
|                                                              |                                                              |              |                                                              |                 |
|                                                              |                                                              |              |                                                              |                 |
|                                                              |                                                              |              |                                                              |                 |
|                                                              |                                                              |              |                                                              |                 |





# Windows版

## Ctrl

| 快捷键           | 介绍                                                         |
| :--------------- | :----------------------------------------------------------- |
| Ctrl + F         | 在当前文件进行文本查找 `（必备）`                            |
| Ctrl + R         | 在当前文件进行文本替换 `（必备）`                            |
| Ctrl + Z         | 撤销 `（必备）`                                              |
| Ctrl + Y         | 删除光标所在行 或 删除选中的行 `（必备）`                    |
| Ctrl + X         | 剪切光标所在行 或 剪切选择内容                               |
| Ctrl + C         | 复制光标所在行 或 复制选择内容                               |
| Ctrl + D         | 复制光标所在行 或 复制选择内容，并把复制内容插入光标位置下面 `（必备）` |
| Ctrl + W         | 递进式选择代码块。可选中光标所在的单词或段落，连续按会在原有选中的基础上再扩展选中范围 `（必备）` |
| Ctrl + E         | 显示最近打开的文件记录列表 `（必备）`                        |
| Ctrl + N         | 根据输入的 **类名** 查找类文件 `（必备）`                    |
| Ctrl + G         | 在当前文件跳转到指定行处                                     |
| Ctrl + J         | 插入自定义动态代码模板 `（必备）`                            |
| Ctrl + P         | 方法参数提示显示 `（必备）`                                  |
| Ctrl + Q         | 光标所在的变量 / 类名 / 方法名等上面（也可以在提示补充的时候按），显示文档内容 |
| Ctrl + U         | 前往当前光标所在的方法的父类的方法 / 接口定义 `（必备）`     |
| Ctrl + B         | 进入光标所在的方法/变量的接口或是定义处，等效于 `Ctrl + 左键单击` `（必备）` |
| Ctrl + K         | 版本控制提交项目，需要此项目有加入到版本控制才可用           |
| Ctrl + T         | 版本控制更新项目，需要此项目有加入到版本控制才可用           |
| Ctrl + H         | 显示当前类的层次结构                                         |
| Ctrl + O         | 选择可重写的方法                                             |
| Ctrl + I         | 选择可继承的方法                                             |
| Ctrl + +         | 展开代码                                                     |
| Ctrl + -         | 折叠代码                                                     |
| Ctrl + /         | 注释光标所在行代码，会根据当前不同文件类型使用不同的注释符号 `（必备）` |
| Ctrl + [         | 移动光标到当前所在代码的花括号开始位置                       |
| Ctrl + ]         | 移动光标到当前所在代码的花括号结束位置                       |
| Ctrl + F1        | 在光标所在的错误代码处显示错误信息 `（必备）`                |
| Ctrl + F3        | 调转到所选中的词的下一个引用位置 `（必备）`                  |
| Ctrl + F4        | 关闭当前编辑文件                                             |
| Ctrl + F8        | 在 Debug 模式下，设置光标当前行为断点，如果当前已经是断点则去掉断点 |
| Ctrl + F9        | 执行 Make Project 操作                                       |
| Ctrl + F11       | 选中文件 / 文件夹，使用助记符设定 / 取消书签 `（必备）`      |
| Ctrl + F12       | 弹出当前文件结构层，可以在弹出的层上直接输入，进行筛选       |
| Ctrl + Tab       | 编辑窗口切换，如果在切换的过程又加按上delete，则是关闭对应选中的窗口 |
| Ctrl + End       | 跳到文件尾                                                   |
| Ctrl + Home      | 跳到文件头                                                   |
| Ctrl + Space     | 基础代码补全，默认在 Windows 系统上被输入法占用，需要进行修改，建议修改为 `Ctrl + 逗号` `（必备）` |
| Ctrl + Delete    | 删除光标后面的单词或是中文句 `（必备）`                      |
| Ctrl + BackSpace | 删除光标前面的单词或是中文句 `（必备）`                      |
| Ctrl + 1,2,3...9 | 定位到对应数值的书签位置 `（必备）`                          |
| Ctrl + 左键单击  | 在打开的文件标题上，弹出该文件路径 `（必备）`                |
| Ctrl + 光标定位  | 按 Ctrl 不要松开，会显示光标所在的类信息摘要                 |
| Ctrl + 左方向键  | 光标跳转到当前单词 / 中文句的左侧开头位置 `（必备）`         |
| Ctrl + 右方向键  | 光标跳转到当前单词 / 中文句的右侧开头位置 `（必备）`         |
| Ctrl + 前方向键  | 等效于鼠标滚轮向前效果 `（必备）`                            |
| Ctrl + 后方向键  | 等效于鼠标滚轮向后效果 `（必备）`                            |

## Alt

| 快捷键                                            | 介绍                                                         |
| :------------------------------------------------ | :----------------------------------------------------------- |
| Alt + `|显示版本控制常用操作菜单弹出层 `（必备）` |                                                              |
| Alt + Q                                           | 弹出一个提示，显示当前类的声明 / 上下文信息                  |
| Alt + F1                                          | 显示当前文件选择目标弹出层，弹出层中有很多目标可以进行选择 `（必备）` |
| Alt + F2                                          | 对于前面页面，显示各类浏览器打开目标选择弹出层               |
| Alt + F3                                          | 选中文本，逐个往下查找相同文本，并高亮显示                   |
| Alt + F7                                          | 查找光标所在的方法 / 变量 / 类被调用的地方                   |
| Alt + F8                                          | 在 Debug 的状态下，选中对象，弹出可输入计算表达式调试框，查看该输入内容的调试结果 |
| Alt + Home                                        | 定位 / 显示到当前文件的 `Navigation Bar`                     |
| Alt + Enter                                       | IntelliJ IDEA 根据光标所在问题，提供快速修复选择，光标放在的位置不同提示的结果也不同 `（必备）` |
| Alt + Insert                                      | 代码自动生成，如生成对象的 set / get 方法，构造函数，toString() 等 `（必备）` |
| Alt + 左方向键                                    | 切换当前已打开的窗口中的子视图，比如Debug窗口中有Output、Debugger等子视图，用此快捷键就可以在子视图中切换 `（必备）` |
| Alt + 右方向键                                    | 按切换当前已打开的窗口中的子视图，比如Debug窗口中有Output、Debugger等子视图，用此快捷键就可以在子视图中切换 `（必备）` |
| Alt + 前方向键                                    | 当前光标跳转到当前文件的前一个方法名位置 `（必备）`          |
| Alt + 后方向键                                    | 当前光标跳转到当前文件的后一个方法名位置 `（必备）`          |
| Alt + 1,2,3...9                                   | 显示对应数值的选项卡，其中 1 是 Project 用得最多 `（必备）`  |

## Shift

| 快捷键               | 介绍                                                         |
| :------------------- | :----------------------------------------------------------- |
| Shift + F1           | 如果有外部文档可以连接外部文档                               |
| Shift + F2           | 跳转到上一个高亮错误 或 警告位置                             |
| Shift + F3           | 在查找模式下，查找匹配上一个                                 |
| Shift + F4           | 对当前打开的文件，使用新Windows窗口打开，旧窗口保留          |
| Shift + F6           | 对文件 / 文件夹 重命名                                       |
| Shift + F7           | 在 Debug 模式下，智能步入。断点所在行上有多个方法调用，会弹出进入哪个方法 |
| Shift + F8           | 在 Debug 模式下，跳出，表现出来的效果跟 `F9` 一样            |
| Shift + F9           | 等效于点击工具栏的 `Debug` 按钮                              |
| Shift + F10          | 等效于点击工具栏的 `Run` 按钮                                |
| Shift + F11          | 弹出书签显示层 `（必备）`                                    |
| Shift + Tab          | 取消缩进 `（必备）`                                          |
| Shift + ESC          | 隐藏当前 或 最后一个激活的工具窗口                           |
| Shift + End          | 选中光标到当前行尾位置                                       |
| Shift + Home         | 选中光标到当前行头位置                                       |
| Shift + Enter        | 开始新一行。光标所在行下空出一行，光标定位到新行位置 `（必备）` |
| Shift + 左键单击     | 在打开的文件名上按此快捷键，可以关闭当前打开文件 `（必备）`  |
| Shift + 滚轮前后滚动 | 当前文件的横向滚动轴滚动 `（必备）`                          |

## Ctrl + Alt

| 快捷键                   | 介绍                                                         |
| :----------------------- | :----------------------------------------------------------- |
| Ctrl + Alt + L           | 格式化代码，可以对当前文件和整个包目录使用 `（必备）`        |
| Ctrl + Alt + O           | 优化导入的类，可以对当前文件和整个包目录使用 `（必备）`      |
| Ctrl + Alt + I           | 光标所在行 或 选中部分进行自动代码缩进，有点类似格式化       |
| Ctrl + Alt + T           | 对选中的代码弹出环绕选项弹出层 `（必备）`                    |
| Ctrl + Alt + J           | 弹出模板选择窗口，将选定的代码加入动态模板中                 |
| Ctrl + Alt + H           | 调用层次                                                     |
| Ctrl + Alt + B           | 在某个调用的方法名上使用会跳到具体的实现处，可以跳过接口     |
| Ctrl + Alt + C           | 重构-快速提取常量                                            |
| Ctrl + Alt + F           | 重构-快速提取成员变量                                        |
| Ctrl + Alt + V           | 重构-快速提取变量                                            |
| Ctrl + Alt + Y           | 同步、刷新                                                   |
| Ctrl + Alt + S           | 打开 IntelliJ IDEA 系统设置 `（必备）`                       |
| Ctrl + Alt + F7          | 显示使用的地方。寻找被该类或是变量被调用的地方，用弹出框的方式找出来 |
| Ctrl + Alt + F11         | 切换全屏模式                                                 |
| Ctrl + Alt + Enter       | 光标所在行上空出一行，光标定位到新行 `（必备）`              |
| Ctrl + Alt + Home        | 弹出跟当前文件有关联的文件弹出层                             |
| Ctrl + Alt + Space       | 类名自动完成                                                 |
| Ctrl + Alt + 左方向键    | 退回到上一个操作的地方 `（必备）`                            |
| Ctrl + Alt + 右方向键    | 前进到上一个操作的地方 `（必备）`                            |
| Ctrl + Alt + 前方向键    | 在查找模式下，跳到上个查找的文件                             |
| Ctrl + Alt + 后方向键    | 在查找模式下，跳到下个查找的文件                             |
| Ctrl + Alt + 右括号（]） | 在打开多个项目的情况下，切换下一个项目窗口                   |
| Ctrl + Alt + 左括号（[） | 在打开多个项目的情况下，切换上一个项目窗口                   |

## Ctrl + Shift

| 快捷键                   | 介绍                                                         |
| :----------------------- | :----------------------------------------------------------- |
| Ctrl + Shift + F         | 根据输入内容查找整个项目 或 指定目录内文件 `（必备）`        |
| Ctrl + Shift + R         | 根据输入内容替换对应内容，范围为整个项目 或 指定目录内文件 `（必备）` |
| Ctrl + Shift + J         | 自动将下一行合并到当前行末尾 `（必备）`                      |
| Ctrl + Shift + Z         | 取消撤销 `（必备）`                                          |
| Ctrl + Shift + W         | 递进式取消选择代码块。可选中光标所在的单词或段落，连续按会在原有选中的基础上再扩展取消选中范围 `（必备）` |
| Ctrl + Shift + N         | 通过文件名定位 / 打开文件 / 目录，打开目录需要在输入的内容后面多加一个正斜杠 `（必备）` |
| Ctrl + Shift + U         | 对选中的代码进行大 / 小写轮流转换 `（必备）`                 |
| Ctrl + Shift + T         | 对当前类生成单元测试类，如果已经存在的单元测试类则可以进行选择 `（必备）` |
| Ctrl + Shift + C         | 复制当前文件磁盘路径到剪贴板 `（必备）`                      |
| Ctrl + Shift + V         | 弹出缓存的最近拷贝的内容管理器弹出层                         |
| Ctrl + Shift + E         | 显示最近修改的文件列表的弹出层                               |
| Ctrl + Shift + H         | 显示方法层次结构                                             |
| Ctrl + Shift + B         | 跳转到类型声明处 `（必备）`                                  |
| Ctrl + Shift + I         | 快速查看光标所在的方法 或 类的定义                           |
| Ctrl + Shift + A         | 查找动作 / 设置                                              |
| Ctrl + Shift + /         | 代码块注释 `（必备）`                                        |
| Ctrl + Shift + [         | 选中从光标所在位置到它的顶部中括号位置 `（必备）`            |
| Ctrl + Shift + ]         | 选中从光标所在位置到它的底部中括号位置 `（必备）`            |
| Ctrl + Shift + +         | 展开所有代码 `（必备）`                                      |
| Ctrl + Shift + -         | 折叠所有代码 `（必备）`                                      |
| Ctrl + Shift + F7        | 高亮显示所有该选中文本，按Esc高亮消失 `（必备）`             |
| Ctrl + Shift + F8        | 在 Debug 模式下，指定断点进入条件                            |
| Ctrl + Shift + F9        | 编译选中的文件 / 包 / Module                                 |
| Ctrl + Shift + F12       | 编辑器最大化 `（必备）`                                      |
| Ctrl + Shift + Space     | 智能代码提示                                                 |
| Ctrl + Shift + Enter     | 自动结束代码，行末自动添加分号 `（必备）`                    |
| Ctrl + Shift + Backspace | 退回到上次修改的地方 `（必备）`                              |
| Ctrl + Shift + 1,2,3...9 | 快速添加指定数值的书签 `（必备）`                            |
| Ctrl + Shift + 左键单击  | 把光标放在某个类变量上，按此快捷键可以直接定位到该类中 `（必备）` |
| Ctrl + Shift + 左方向键  | 在代码文件上，光标跳转到当前单词 / 中文句的左侧开头位置，同时选中该单词 / 中文句 `（必备）` |
| Ctrl + Shift + 右方向键  | 在代码文件上，光标跳转到当前单词 / 中文句的右侧开头位置，同时选中该单词 / 中文句 `（必备）` |
| Ctrl + Shift + 前方向键  | 光标放在方法名上，将方法移动到上一个方法前面，调整方法排序 `（必备）` |
| Ctrl + Shift + 后方向键  | 光标放在方法名上，将方法移动到下一个方法前面，调整方法排序 `（必备）` |

## Alt + Shift

| 快捷键                 | 介绍                                                         |
| :--------------------- | :----------------------------------------------------------- |
| Alt + Shift + N        | 选择 / 添加 task `（必备）`                                  |
| Alt + Shift + F        | 显示添加到收藏夹弹出层 / 添加到收藏夹                        |
| Alt + Shift + C        | 查看最近操作项目的变化情况列表                               |
| Alt + Shift + I        | 查看项目当前文件                                             |
| Alt + Shift + F7       | 在 Debug 模式下，下一步，进入当前方法体内，如果方法体还有方法，则会进入该内嵌的方法中，依此循环进入 |
| Alt + Shift + F9       | 弹出 `Debug` 的可选择菜单                                    |
| Alt + Shift + F10      | 弹出 `Run` 的可选择菜单                                      |
| Alt + Shift + 左键双击 | 选择被双击的单词 / 中文句，按住不放，可以同时选择其他单词 / 中文句 `（必备）` |
| Alt + Shift + 前方向键 | 移动光标所在行向上移动 `（必备）`                            |
| Alt + Shift + 后方向键 | 移动光标所在行向下移动 `（必备）`                            |

## Ctrl + Shift + Alt

| 快捷键                 | 介绍                        |
| :--------------------- | :-------------------------- |
| Ctrl + Shift + Alt + V | 无格式黏贴 `（必备）`       |
| Ctrl + Shift + Alt + N | 前往指定的变量 / 方法       |
| Ctrl + Shift + Alt + S | 打开当前项目设置 `（必备）` |
| Ctrl + Shift + Alt + C | 复制参考信息                |

## 其他

| 快捷键        | 介绍                                                         |
| :------------ | :----------------------------------------------------------- |
| F2            | 跳转到下一个高亮错误 或 警告位置 `（必备）`                  |
| F3            | 在查找模式下，定位到下一个匹配处                             |
| F4            | 编辑源 `（必备）`                                            |
| F7            | 在 Debug 模式下，进入下一步，如果当前行断点是一个方法，则进入当前方法体内，如果该方法体还有方法，则不会进入该内嵌的方法中 |
| F8            | 在 Debug 模式下，进入下一步，如果当前行断点是一个方法，则不进入当前方法体内 |
| F9            | 在 Debug 模式下，恢复程序运行，但是如果该断点下面代码还有断点则停在下一个断点上 |
| F11           | 添加书签 `（必备）`                                          |
| F12           | 回到前一个工具窗口 `（必备）`                                |
| Tab           | 缩进 `（必备）`                                              |
| ESC           | 从工具窗口进入代码文件窗口 `（必备）`                        |
| 连按两次Shift | 弹出 `Search Everywhere` 弹出层                              |

# Mac版

## Mac键盘符号和修饰键说明

- `⌘` Command
- `⇧` Shift
- `⌥` Option
- `⌃` Control
- `↩︎` Return/Enter
- `⌫` Delete
- `⌦` 向前删除键（Fn+Delete）
- `↑` 上箭头
- `↓` 下箭头
- `←` 左箭头
- `→` 右箭头
- `⇞` Page Up（Fn+↑）
- `⇟` Page Down（Fn+↓）
- `Home` Fn + ←
- `End` Fn + →
- `⇥` 右制表符（Tab键）
- `⇤` 左制表符（Shift+Tab）
- `⎋` Escape (Esc)

## 一、Editing（编辑）

- `Control + Space` 基本的代码补全（补全任何类、方法、变量）
- `Control + Shift + Space` 智能代码补全（过滤器方法列表和变量的预期类型）
- `Command + Shift + Enter` 自动结束代码，行末自动添加分号
- `Command + P` 显示方法的参数信息
- `Control + J` 快速查看文档
- `Shift + F1` 查看外部文档（在某些代码上会触发打开浏览器显示相关文档）
- `Command + 鼠标放在代码上` 显示代码简要信息
- `Command + F1` 在错误或警告处显示具体描述信息
- `Command + N, Control + Enter, Control + N` 生成代码（getter、setter、构造函数、hashCode/equals,toString）
- `Control + O` 覆盖方法（重写父类方法）
- `Control + I` 实现方法（实现接口中的方法）
- `Command + Option + T` 包围代码（使用if..else, try..catch, for, synchronized等包围选中的代码）
- `Command + /` 注释/取消注释与行注释
- `Command + Option + /` 注释/取消注释与块注释
- `Option + 方向键上` 连续选中代码块
- `Option + 方向键下` 减少当前选中的代码块
- `Control + Shift + Q` 显示上下文信息
- `Option + Enter` 显示意向动作和快速修复代码
- `Command + Option + L` 格式化代码
- `Control + Option + O` 优化import
- `Control + Option + I` 自动缩进线
- `Tab / Shift + Tab` 缩进代码 / 反缩进代码
- `Command + X` 剪切当前行或选定的块到剪贴板
- `Command + C` 复制当前行或选定的块到剪贴板
- `Command + V` 从剪贴板粘贴
- `Command + Shift + V` 从最近的缓冲区粘贴
- `Command + D` 复制当前行或选定的块
- `Command + Delete` 删除当前行或选定的块的行
- `Control + Shift + J` 智能的将代码拼接成一行
- `Command + Enter` 智能的拆分拼接的行
- `Shift + Enter` 开始新的一行
- `Command + Shift + U` 大小写切换
- `Command + Shift + ] / Command + Shift + [` 选择直到代码块结束/开始
- `Option + Fn + Delete` 删除到单词的末尾
- `Option + Delete` 删除到单词的开头
- `Command + 加号 / Command + 减号` 展开 / 折叠代码块
- `Command + Shift + 加号` 展开所以代码块
- `Command + Shift + 减号` 折叠所有代码块
- `Command + W` 关闭活动的编辑器选项卡

## 二、Search/Replace（查询/替换）

- `Double Shift` 查询任何东西
- `Command + F` 文件内查找
- `Command + G` 查找模式下，向下查找
- `Command + Shift + G` 查找模式下，向上查找
- `Command + R` 文件内替换
- `Command + Shift + F` 全局查找（根据路径）
- `Command + Shift + R` 全局替换（根据路径）
- `Command + Shift + S` 查询结构（Ultimate Edition 版专用，需要在Keymap中设置）
- `Command + Shift + M` 替换结构（Ultimate Edition 版专用，需要在Keymap中设置）

## 三、Usage Search（使用查询）

- `Option + F7 / Command + F7` 在文件中查找用法 / 在类中查找用法
- `Command + Shift + F7` 在文件中突出显示的用法
- `Command + Option + F7` 显示用法

## 四、Compile and Run（编译和运行）

- `Command + F9` 编译Project
- `Command + Shift + F9` 编译选择的文件、包或模块
- `Control + Option + R` 弹出 Run 的可选择菜单
- `Control + Option + D` 弹出 Debug 的可选择菜单
- `Control + R` 运行
- `Control + D` 调试
- `Control + Shift + R, Control + Shift + D` 从编辑器运行上下文环境配置

## 五、Debugging（调试）

- `F8` 进入下一步，如果当前行断点是一个方法，则不进入当前方法体内
- `F7` 进入下一步，如果当前行断点是一个方法，则进入当前方法体内，如果该方法体还有方法，则不会进入该内嵌的方法中
- `Shift + F7` 智能步入，断点所在行上有多个方法调用，会弹出进入哪个方法
- `Shift + F8` 跳出
- `Option + F9` 运行到光标处，如果光标前有其他断点会进入到该断点
- `Option + F8` 计算表达式（可以更改变量值使其生效）
- `Command + Option + R` 恢复程序运行，如果该断点下面代码还有断点则停在下一个断点上
- `Command + F8` 切换断点（若光标当前行有断点则取消断点，没有则加上断点）
- `Command + Shift + F8` 查看断点信息

## 六、Navigation（导航）

- `Command + O` 查找类文件
- `Command + Shift + O` 查找所有类型文件、打开文件、打开目录，打开目录需要在输入的内容前面或后面加一个反斜杠`/`
- `Command + Option + O` 前往指定的变量 / 方法
- `Control + 方向键左 / Control + 方向键右` 左右切换打开的编辑tab页
- `F12` 返回到前一个工具窗口
- `Esc` 从工具窗口进入代码文件窗口
- `Shift + Esc` 隐藏当前或最后一个活动的窗口，且光标进入代码文件窗口
- `Command + Shift + F4` 关闭活动run/messages/find/... tab
- `Command + L` 在当前文件跳转到某一行的指定处
- `Command + E` 显示最近打开的文件记录列表
- `Option + 方向键左 / Option + 方向键右` 光标跳转到当前单词 / 中文句的左 / 右侧开头位置
- `Command + Option + 方向键左 / Command + Option + 方向键右` 退回 / 前进到上一个操作的地方
- `Command + Shift + Delete` 跳转到最后一个编辑的地方
- `Option + F1` 显示当前文件选择目标弹出层，弹出层中有很多目标可以进行选择(如在代码编辑窗口可以选择显示该文件的Finder)
- `Command + B / Command + 鼠标点击` 进入光标所在的方法/变量的接口或是定义处
- `Command + Option + B` 跳转到实现处，在某个调用的方法名上使用会跳到具体的实现处，可以跳过接口
- `Option + Space, Command + Y` 快速打开光标所在方法、类的定义
- `Control + Shift + B` 跳转到类型声明处
- `Command + U` 前往当前光标所在方法的父类的方法 / 接口定义
- `Control + 方向键下 / Control + 方向键上` 当前光标跳转到当前文件的前一个/后一个方法名位置
- `Command + ] / Command + [` 移动光标到当前所在代码的花括号开始/结束位置
- `Command + F12` 弹出当前文件结构层，可以在弹出的层上直接输入进行筛选（可用于搜索类中的方法）
- `Control + H` 显示当前类的层次结构
- `Command + Shift + H` 显示方法层次结构
- `Control + Option + H` 显示调用层次结构
- `F2 / Shift + F2` 跳转到下一个/上一个突出错误或警告的位置
- `F4 / Command + 方向键下` 编辑/查看代码源
- `Option + Home` 显示到当前文件的导航条
- `F3`选中文件/文件夹/代码行，添加/取消书签
- `Option + F3` 选中文件/文件夹/代码行，使用助记符添加/取消书签
- `Control + 0...Control + 9` 定位到对应数值的书签位置
- `Command + F3` 显示所有书签

## 七、Refactoring（重构）

- `F5` 复制文件到指定目录
- `F6` 移动文件到指定目录
- `Command + Delete` 在文件上为安全删除文件，弹出确认框
- `Shift + F6` 重命名文件
- `Command + F6` 更改签名
- `Command + Option + N` 一致性
- `Command + Option + M` 将选中的代码提取为方法
- `Command + Option + V` 提取变量
- `Command + Option + F` 提取字段
- `Command + Option + C` 提取常量
- `Command + Option + P` 提取参数

## 八、VCS/Local History（版本控制/本地历史记录）

- `Command + K` 提交代码到版本控制器
- `Command + T` 从版本控制器更新代码
- `Option + Shift + C` 查看最近的变更记录
- `Control + C` 快速弹出版本控制器操作面板

## 九、Live Templates（动态代码模板）

- `Command + Option + J` 弹出模板选择窗口，将选定的代码使用动态模板包住
- `Command + J` 插入自定义动态代码模板

## 十、General（通用）

- `Command + 1...Command + 9` 打开相应编号的工具窗口
- `Command + S` 保存所有
- `Command + Option + Y` 同步、刷新
- `Control + Command + F` 切换全屏模式
- `Command + Shift + F12` 切换最大化编辑器
- `Option + Shift + F` 添加到收藏夹
- `Option + Shift + I` 检查当前文件与当前的配置文件
- Control + ` 快速切换当前的scheme（切换主题、代码样式等）
- `Command + ,` 打开IDEA系统设置
- `Command + ;` 打开项目结构对话框
- `Shift + Command + A` 查找动作（可设置相关选项）
- `Control + Shift + Tab` 编辑窗口标签和工具窗口之间切换（如果在切换的过程加按上delete，则是关闭对应选中的窗口）

## 十一、Other（一些官方文档上没有体现的快捷键）

- `Command + Shift +8` 竖编辑模式