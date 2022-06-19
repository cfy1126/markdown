# 核心组件

## BrowserRouter

- `BrowserRouter`声明当前要用的一个非hash模式的路由（使用h5的histor.pushState API实现）

## Link

- 渲染的结果是`a`标签，`to`属性渲染成`href`

## Routes

- 相对于**Vue**的`router-view`

## Route

- 匹配路由

## 编程式路由跳转

- ```react
  //方法形式
  import { useNavigate } from 'react-router-dom'
  
  const navigate = useNavigate()
   navigate('/', { replace: true })
  ```

- ```react
  //z
  import { Navigate } from 'react-router-dom'
  
  <Navigate to="/login" replace />
  ```

  