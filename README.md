
package selenium;

import org.openqa.selenium.By;
import org.openqa.selenium.Keys;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;


public class FirstScript {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.setProperty("webdriver.chrome.driver","C:\\Users\\Gomotse\\Documents\\selenium-java-4.4.0\\chromedriver.exe");
    WebDriver driver = new ChromeDriver();
    driver.get("https://www.google.com/");
    //driver.navigate().to("https://www.google.com/");
    driver.findElement(By.name("q")).sendKeys("types of summer dresses" + Keys.ENTER);
    
    
	}

}
