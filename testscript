from selenium import webdriver

# ChromeOptions
chrome_options = webdriver.ChromeOptions()
chrome_options.add_argument('--headless')
chrome_options.add_argument('--no-sandbox') # required if running as root user. 

# Test
driver = webdriver.Chrome(options=chrome_options)
driver.get('https://www.google.com')
print(driver.title)
