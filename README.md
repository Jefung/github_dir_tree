# github_dir_tree

自动读取文件/文件夹描述, 生成 `markdown` 形式的项目结构树

## 截图

![serial_module_screenshot.jpg](http://images.jefung.cn/serial_module_screenshot.jpg)

## 待做

- [x] 支持文件/目录描述
- [x] 支持 `gitingore` 语法过滤文件,支持自动读取`.gitignore`过滤文件
- [x] 自动增加/更新到`README.md`文件
- [x] 支持文件/目录描述
- [ ] 支持多个描述符匹配
- [ ] 各种形式打印并输出到各类文件中
- [ ] 生成exe
- [ ] 重构读取配置文件和获取标准输入的代码

## 安装
* pip: `pip install pip install github_dir_tree`

## 使用

* cmd: `python -m github_dir_tree.main [文件夹路径]`

## 注意
1. 第一次使用时会自动在目标文件夹下生成`.github_dir_tree` 配置文件, 你可以在配置文件里面修改配置
2. 自动读取`.gitignore`文件并自动过滤
3. 默认 `.dir_description` 为文件夹描述符
