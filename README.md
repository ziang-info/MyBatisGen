# MyBatisGen
MyBatis Generator Demo (Maven)


Main files:
	pom.xml: Project Management: dependencies & plugins
	generatorConfig.xml : Generator config file: Database connection & Ouput config
	mysql-connector-java-5.1.47.jar	: MySql connect driver

Commands:
	mvn mybatis-generator:generate
	mvn -Dmybatis.generator.overwrite=true mybatis-generator:generate

Reference:
	http://www.mybatis.org/generator


	