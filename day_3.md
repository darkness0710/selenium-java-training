### Refer: 
https://www.youtube.com/watch?v=dbzc9UbFZt8&t=926s

## Download chromedriver
- Link: https://chromedriver.chromium.org/downloads
- Kiểm tra version chorme hiện tại trên máy tính và tải chorme drive tương ứng với version chorme trên máy. (chromedriver_win32.zip)

## Download Selenium Java (JAR)
- Link: https://www.selenium.dev/downloads/ (Bên cạnh chữ Latest stable version )

## Download file day_3.html
- Link: https://github.com/darkness0710/selenium-java-training/tree/main/assets

## Source code example get value input email by name
- Ví dụ về việc lấy giá trị ô input email theo input name và in ra console.
```
package Example;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.By;

public class App {
    public static void main(String[] args)
    {
        System.setProperty("webdrive.chrome.driver", "D:\\selenium-java-training");
        WebDriver driver = new ChromeDriver();
        driver.get("file:///D:/selenium-java-training/day_3.html");
        String email = driver.findElement(By.name("email")).getAttribute("value");
        System.out.println(email);
        // driver.quit();
    }
}

```
![image](https://user-images.githubusercontent.com/25264763/206482829-f1f5c11d-54b7-4d40-b27c-737df1548104.png)
