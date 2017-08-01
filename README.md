# maven-profile
三种方式实现多环境打包部署

1. 利用Spring的profile机制来实现
  1. 缺点是依赖spring环境
  2. 该项目中默认被注释
2. 利用maven的profile机制来实现
  1. 缺点是依赖maven环境
  2. 该项目中默认被注释
3. 利用maven的+resources+filter机制来实现
  1. 缺点是依赖maven环境
  2. 该项目中默认是这种方式实现
4. 关于使用方式，参见博客：http://www.cnblogs.com/hafiz/p/7269148.html
