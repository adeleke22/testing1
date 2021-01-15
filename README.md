# testing1
package Selenuim_Deko;

import org.openqa.selenium.By;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.remote.RemoteWebDriver;

public class Deko {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		System.setProperty("webdriver.chrome.driver", "C:\\Users\\koduk\\eclipse-workspace\\Selenuim software\\chromedriver.exe");
		
		RemoteWebDriver driver = new ChromeDriver();
		driver.get("https://www.dekopay.com/");
		
		driver.manage().window().maximize();
		driver.findElement(By.className(null));
		driver.findElement(By.className(null));
		//driver.sel
	}

}
