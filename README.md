# mlaction

[![Build Status](https://travis-ci.org/iOSDevLog/mlaction.svg?branch=master)](https://travis-ci.org/iOSDevLog/mlaction)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mlaction.svg)
![PyPI](https://img.shields.io/pypi/v/mlaction.svg)
![PyPI - License](https://img.shields.io/pypi/l/mlaction.svg)
![PyPI - Wheel](https://img.shields.io/pypi/wheel/mlaction.svg)
![PyPI - Downloads](https://img.shields.io/pypi/dm/mlaction.svg)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/iOSDevLog/mlaction.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FiOSDevLog%2Fmlaction)

Machine Learning in Action 机器学习实战 Python3

GitHub: <https://github.com/iOSDevLog/mlaction>

## 方法

## 截图

## PyPI 境像加速

```python
pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple mlaction
```

## 代码规范

参考：<https://docs.python.org/3/tutorial>

### .vscode/settings.json

```json
{
  "python.pythonPath": "/Users/iosdevlog/.Envs/mlaction/bin/python",
  "python.linting.flake8Enabled": true,
  "python.formatting.provider": "yapf",
  "python.linting.flake8Args": ["--max-line-length=248"],
  "python.linting.pylintEnabled": false
}
```

- 字符串使用双引号： **""**

## 安装

```sh
pip install mlaction
```

## 开发

### 本地开发

```sh
pip3 install -e .
```

### 测试

```sh
pytest mlaction
```

### 发布

```sh
python3 setup.py sdist bdist_wheel
twine upload dist/*
```

### 生成CHANGELOG

```
npm install -g conventional-changelog-cli
./version.sh
```

### 联系方式

网站: [http://2019.iosdevlog.com/](https://2019.iosdevlog.com/)

微信公众号: AI 开发日志

![AIDevLog](https://2019.iosdevlog.com/uploads/AIDevLog.jpg)

## License

mlaction is released under the MIT license. See [LICENSE](LICENSE) for details.
