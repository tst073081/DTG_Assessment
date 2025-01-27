# DTG_Assessment

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
 
public class PracticeSoftwareTestingAutomation {
    public static void main(String[] args) {
        // 1. Set up WebDriver and navigate to website
        System.setProperty("webdriver.chrome.driver", "path/to/chromedriver");
        WebDriver driver = new ChromeDriver();
        driver.get("https://secure-web.cisco.com/1cdam65zhWPzfFQlvuMGcLRa3PPZ4vsSxJBgF7y4VsmJRZqlbcXemcsXRZsDuaCl0TtkGiskoIUrfOknxmCnGfBGmwuotcchyuQnAnb9JR-huyTwZG5b4dqstU7ytNNqWgQsnYJFy0HlJcPaBGTxdymS6VbksVRvnQdqojoxVqXoiq4p0KyFjQGUmyf9KGKEH1kV5fNjNva36owfE8kmyQuQfMAspsR7TL8EqJIoEnWtU8Ta4ia0a5xeQ4YwBkGVzaUCDLsQv67PGfnVrUx5BzMBRKJ8TPxulXD97d8IEkpRaBqBe9DplOLAcE6FosgAm/https%3A%2F%2Fpracticesoftwaretesting.com%2F");
 
        // 2. Register User
        //   * Locate and click "Register" link
        //   * Fill in required registration details
        //   * Submit registration
 
        // 3. Login User
        //   * Locate and click "Login" link
        //   * Fill in username / password
        //   * Submit login
 
        // 4. Click on a product and add to cart
        //   * Identify product, click Add to Cart
 
        // 5. Go to Cart and Checkout
        //   * Validate items in the cart
        //   * Click Checkout
 
        // 6. Fill in Checkout Info & Complete Transaction
        //   * Fill in shipping / billing info
        //   * Validate success message or redirection
 
        // Close the browser
        driver.quit();
    }
}
