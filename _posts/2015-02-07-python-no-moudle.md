---
layout: default
title: Cygwin中使用Python时报错
---

# 在Cygwin中使用Python时，提示
	ImportError: No moudle named site

- 将Python中的模块加入PYTHONPATH环境变量中，如下
	PYTHONPATH=/lib/python2.7:/lib/python2.7/site-packages

	export PYTHONPATH
