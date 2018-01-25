Reast API v1 目录

接口返回参数概览：
 * `status` ：请求状态 0请求成功 -1 Token不正确 
 * `result` : 请求结果数
 * `msg` ： 请求结果信息说明
 * `data`:返回的数据对象、数组等 具体接口装入具体数据
 
 **status**：响应状态码说明：
  - `0`： 表示数据请求合法数据筛选成功
  - `-1`： Token不合法 或者过期 需要登录 默认返回此项目
  - `1`： 请求数据不完整，没有传参，少了参数等
  - `2`： 参数不正确 登录时候表示密码不正确
  - `3`： 用户没有权限请求该地址数据 所属用户的role_id不在列
  - `4`： 查询所指定的参数数据不存在，返回空的结果，数据库查不到内容
  - `5`： 相关的结果解析失败 try... null等 或Token过期 无效 解析失败
  - `6`： 
  - `7`：
  - `8`：
  - `9`：
  - `10`：