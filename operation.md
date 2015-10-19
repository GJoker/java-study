# 正则表达式



---

####正则表达式对字符串的常见操作：

 1. 匹配。
    使用的是String类中的matches方法。
 2. 切割。
    使用的是String类中的split方法。
 3. 替换。
    使用的是String类中的replaceAll方法。
 4. 获取。
    - 将正则规则进行对象的封装。
    ```java
    Pattern p = Pattern.compile(regex);
    
    ```
    - 通过正则对象的matcher方法字符串相关联。获取要对字符串操作的匹配器对象matcher。
    ```java
    Matcher m = p.matcher(str);
    ```
    - 通过matcher匹配器对象的方法对字符串进行操作。
    ```java
    boolean b = m.matches();
    ```

    

 
