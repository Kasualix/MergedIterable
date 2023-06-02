# MergedIterable
我自己在做 [PotatoRunner](https://github.com/MCTeamPotato/PotatoRunner) 时想出来的一个轮子（可能有别的什么 Java 开源仓库已经想出来过了，不过我不在乎）。

我很喜欢它，于是打算分出来单独开个 repo。

# 功能
字面意思，合并的 Iterable。新建一个：`new MergedIterable(iterable1, iterable2)`，然后放手去用吧！

我只是不想在遇到两个需要合并起来处理的`Iterable`时得手动把它们转成`List`再`addAll`，这样太消耗性能了，就想出了这个。
