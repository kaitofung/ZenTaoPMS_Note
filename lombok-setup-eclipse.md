# Lombok在Eclipse中的安装与配置

1. 先到[官网](https://projectlombok.org/download)下载lombok.jar到eclipse.ini同级的目录下
2. 点击jar包进行安装
3. 编辑eclipse.ini文件，在最后一行添加`  -vmargs -javaagent:lombok.jar` 
4. 重启Eclipse
5. 点击导航栏的Project-clean project
6. 在Maven文件中添加依赖

	    	<dependency>
			    <groupId>org.projectlombok</groupId>
			    <artifactId>lombok</artifactId>
			    <version>${lombok.version}</version>
			    <scope>provided</scope>
			</dependency>


