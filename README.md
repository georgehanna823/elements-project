# Automation Project

*Structure for creating a Basic Java Project.*

**Java 7**

* Maven
* TestNG 6.11
* Selenium 2.53


	1. Locate the items listed for msn.com, imdb.com, and a corporate website of your choice using the PageObject approach. You will want to create a separate test case for every element you want to locate which is for a different domain or website. You can use the images at the bottom of this page to help better determine the items you are locating. I will leave it pretty open to what specific element (sometimes there are multiple tags to represent an element) just choose an element relatively close to what I describe as the element. You should have 1 test case in each class IMDBElementsTest and MSNElementsTest, and your choice of two from your own domain.
		* Locate the following items by any of the location strategies at [msn](http://msn.com):
		* 
			1. Today's weather image element.

			2. The first item in most viewed section.
			3. The first button within Sports menu bar.
			4. The first link to an article under News.

		* Locate the following items by any of the location strategies at [imdb](http://imdb.com):
		* 
			1. The first item under New on TV Tonight.
			2. An image of someone who was born Today.
			3. Text for the first item under Latest News.
			4. The location of a png image on the page.


	* 
		* Locate your choose of any 4 items by any of the location strategies at two of the following urls using the PageObject approach, also create a method which clicks on an item you located:
		* 
			1. http://www.shell.com
			2. http://www.usa.siemens.com
			3. http://eni.com
			4. http://sap.com
			5. http://bp.com
			6. http://unilever.com
			7. http://nestle.com
			8. http://roche.com
			9. http://novartis.com
			10. http://gsk.com


	* Helper Methods (AutoBasics). Create the following helper methods:
	* 
		* Create any of these 4 helper methods which locates elements and returns back a List Collection using any strategy, the following are a couple examples:
		* 
			* public static List<WebElement> getPictures(WebDriver driver);
			* public static List<WebElement> getLinks(WebDriver driver);
			* public static List<String> getTextContents(WebDriver driver, By locator); //*.getText()
			* public static List<WebElement> getByTagName(WebDriver driver, String tagName);


		* BONUS: Create a helper method which locates all elements on a page and stores them inside a List Collection using a CSS value (Not CSS Strategy):
		* 
			* public static List<WebElement> getCSSPropBasedElements(WebDriver driver, By locator, String prop, String value);








[George Hanna](https://github.com/georgehanna823)
