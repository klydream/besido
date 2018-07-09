# besido
开发日志
基于zenodo开发，
1、添加一个comment功能，基于record开发，基于bucket保存文件。所以通过/api/deposit/depositions申请，发现这个blueprint其实是create record的。不单单create bucket。所以为了简单，先屏蔽result.html里面关于draft的，无文件的。
