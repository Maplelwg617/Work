# week1

## docker启动

    - winpty docker run -it ubuntu-sex
    - 将代码复制到Ubuntu-Sextractor文件夹中进行使用
    - 需注意改动Dockerfile文件之后，要重新构建环境

## SExtractor启动

    - source-extractor
    - 调整参数
        1. source-extractor -dd(创建需要输出数据及其参数)
        2. cat仅打开文件 vi打开并修改文件
        3. source-extractor -dp（选择需要输出的数据）
    - source-extractor <image> [<image2>][-c <configuration_file>][-<keyword]

## pytorch模型构建

    -暂时还不会，学习当中