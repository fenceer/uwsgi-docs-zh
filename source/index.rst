.. uwsgi-zh documentation master file, created by
   sphinx-quickstart on Mon Jan 28 16:31:20 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

uWSGI 项目简介
==============
uWSGI 项目旨在为部署分布式集群网络应用开发一个完整的解决方案。

uWSGI主要面向web及其标准服务，已经成功的应用于多种不同的语言。

由于uWSGI的可扩展架构，它能够被无限制的扩展用来支持更多的平台和语言。目前，你可以使用C，C++和Objective-C来编写插件。

项目名字中的“WSGI”是为了向同名的Python Web标准表示感谢，因为WSGI为该项目开发了第一个插件。

uWSGI具有跨平台，高性能，低资源消耗，稳定性的优势。

项目组件（更新至最新稳定版）
============================
核心（配置，进程管理，socket创建，监控，日志，内存共享区域，进程通信，集群管理和订阅系统）

请求插件（已实现应用服务接口的各种语言和平台：WSGI, PSGI, Rack, Lua WSAPI, CGI, PHP, Go ...）

Gateways（负载均衡，路由代理）

主进程（大量实例的监视和管理）

循环引擎（高并发，组件预热，多线程，异步事件处理，green thread/coroutine modes。多种技术支持，包括uGreen, Greenlet, Stackless, Gevent, Goroutines and Fibers）

.. note::

	像uWSGI这样的大型开源项目，代码和文档不一定及时同步。邮件列表是最好的帮助来源。

Contents:

.. toctree::
   :maxdepth: 2



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

