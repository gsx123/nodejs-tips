# winston日志框架使用

原来一直是使用`log4js`做日志输出，原来只是输出到标准输出中，用了3年了，一直没换过。现
在为了将详细的日志都记录下来，不光输出到标准出，而且根据服务的分层输出到不同的文件中。
如：全部的log都输出到debug文件及标准输出中，service层的log输出service.log文件中，
dao层的log输出到dao.log文件中。