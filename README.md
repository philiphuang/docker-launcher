# docker-launcher
docker launcher kit, including launching scripts and project template.
  - launching scripts
    1. Command-line console,
    1. basic docker management like start/stop containers or entering docker shell in a single CLI interface with build-in scripts
    1. customized management like backup/restore, showing container IP with your own scripts.
    1. You could manage single project or multiple projects all-in-one folder, or even multiple projects in multiple folders, at your own choice with help from project template.
  - project template: docker-compose project file structure

Docker 启动工具箱，包含启动脚本和项目目录模板。
  - 启动脚本
    1. 命令行控制台，省去重复敲打docker-compose命令的负担
    1. 预置的功能，如启动、关闭、重启容器、查看容器日志，进入容器的shell
    1. 可运行用户自定义脚本
    1. 在一个目录下，支持单个或多个项目（建议按照目录模板放置文件，保持目录整洁），也支持基于相同的项目，不同使用场景和频度的脚本，例如备份、还原、升级。
  - 项目文件夹范例
    1. 如果一个目录下容纳多个项目，可以按项目维度管理（project1-n），也可以按备份维度管理（代码，需备份的数据，可丢弃的日志等）