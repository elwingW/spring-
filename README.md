此项目若要成功运行，需要下载mysql5系列的版本，并给数据库中创建一个test数据库，再给数据库中创建一个student数据表，代码如下
CREATE TABLE Student(
   ID   INT NOT NULL AUTO_INCREMENT,
   NAME VARCHAR(20) NOT NULL,
   AGE  INT NOT NULL,
   PRIMARY KEY (ID)
);
