# dionysus
[nek-ui](https://github.com/kaola-fed/nek-ui) snippets for VSCode & Atom & Sumlime Text

## VSCode

File > Preferences (Code > Preferences on Mac) > Snippets，选择 HTML，把 [snippets.json](vscode/snippets.json) 内容拷贝进去

![vscode](https://user-images.githubusercontent.com/2230882/28130899-dd4bf170-676a-11e7-9ecf-40286d610f97.gif)

## Atom

File > Snippets，把 [snippets.cson](atom/snippets.cson) 内容拷贝进去

![atom](https://user-images.githubusercontent.com/2230882/28130898-dd400edc-676a-11e7-9535-1a8242200741.gif)

## Sublime Text

Preferences > Browse Packages > User，下载 [nek-ui.sublime-completions](sublime/nek-ui.sublime-completions)，放到 Sublime 用户目录下

> Sublime Text 默认使用 `crtl+space` 作为呼出预览列表命令 `auto_complete` 的快捷键，如果冲突请重新设置其它快捷键

![sublime](https://user-images.githubusercontent.com/2230882/28130897-dd26a1c2-676a-11e7-9872-403171af958a.gif)

## 需要更新？

基于 VSCode Snippets 写的，然后转到 Atom 和 Sublime Text 的格式，如果有修改，**只需要需改** `vscode/snippets.json`，然后 `npm run build` 即可