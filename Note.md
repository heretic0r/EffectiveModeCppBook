# Effective Modern C++

## 简介

C++11 最普遍的特性是移动语义,移动语义的基石是从那些左值中区分处右值 .
* 如果可以取地址,它基本就是一个左值.
* 所有的参数都是左值  **当处理右值引用的参数时,需要铭记,参数本身是个左值**
