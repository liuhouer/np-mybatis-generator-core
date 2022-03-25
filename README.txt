np-mybatis-generator-core-1.3.2.jar 是自己编译的，会生成字段注释
mybatis-generator-core-1.3.2.jar 是官方的，会生成官方注释

备注设置 suppressAllComments可以关闭所有注释
<!-- 备注设置 -->
		<commentGenerator type="org.mybatis.generator.internal.DefaultCommentGenerator">
			<!--  <property name="suppressAllComments" value="false" /> -->
		</commentGenerator>