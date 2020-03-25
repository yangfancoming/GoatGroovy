# Groovy 环境搭建
    第一步：下载并解压
    下载地址：http://groovy-lang.org/download.html
    apache-groovy-sdk-3.0.2.zip
    
    
    新建一个Project，选择Groovy，注意要选择Project SDK和Groovy library，默认是没有Groovy library的，
    选择右边的 create 按钮 ，之后选择自己安装groovy的目录即可 （ F:\Package\Groovy_Environment\groovy-3.0.2）
    然后点击next ，写入工程名称和选择存储位置，点击finish；
    右键src新建一个Groovy文件，选择Groovy Script  
    
    class App {
    
        static void main(args) {
            def mygreeting = "Hello World"
            println mygreeting
        }
    
    }