## 基本数据类型

- 使用`char`类型数据时，要特别注意要不要符号
- `常量`: #define BOSS "我"
- `字符串声明`:
    ```C
    // 字符串以 \0 表示结束
    char name[3] = {'a', 'b', '\0'};
    char name[] = "你好啊";
    // 单独访问
    char name[1];
    ```
- `类型强转`: int a = `(double)` b;