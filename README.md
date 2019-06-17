# cms
海洋cms

海洋cms安装必要说明
1.上传upload到服务器
2.将海洋CMS.rar解压后的文件覆盖upload对应的文件
3.进入海洋cms的后台,将系统选项中的模板文件所在文件夹修改为 mb
4.如果不是根目录修改js/play.js 的appendFrm函数路径改为 document.getElementById("cciframe").src = '/根目录名/js/player/'+ pn + '.html';

