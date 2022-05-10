#junit demo 记录

## 1、引入junit5依赖
    <dependency>
    <groupId>org.junit.jupiter</groupId>’
    <artifactId>junit-jupiter-engine</artifactId>
    <version>5.5.2</version>
    <scope>test</scope>
    </dependency>
    <build>
        <plugins>
		  <plugin>
			<groupId>org.apache.maven.plugins</groupId>
			<artifactId>maven-surefire-plugin</artifactId>
			<version>3.0.0-M3</version>
		</plugin>
	</plugins>
    </build> 
