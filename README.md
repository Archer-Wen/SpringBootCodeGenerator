# SpringBootCodeGenerator
在Moshow郑锴 moshowgame的项目基础上，针对自己日常使用的情况和习惯部分修改，如喜欢原项目，请移步：
``https://github.com/moshowgame/SpringBootCodeGenerator``
### 本项目修改范围
- 在实体类名后面加上spring-boot推荐的Entity字段
- 在实体类的get和set方法上加上注释
- 修改mybatis的xml文件中update语句，新增动态if判空
- 修改mybatis的xml文件中insert语句，新增动态插入判空，符合mybatisGenerator标准
- 修改insert语句，增加插入行主键的返回
- 修改所有的id为id_
- 删除update语句最后的 ``UpdateTime = NOW()``
- 修改dao接口文件的方法注释，更符合javaDoc的标准
- 修改load的方法名为selectByPrimaryKey
- 修改dao文件所有参数为包装类
- 删除dao接口 ``pageListCount()``方法中无用的分页参数
- 修改dao接口注解为@Repository

#### update by Archer-Wen
如喜欢本项目，欢迎star & fork