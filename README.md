# automation

from selenium import webdriver

driver = webdriver.Chrome(executable_path = "C:\\chromedriver.exe")
driver.get("http://edupro.s3-website.ap-south-1.amazonaws.com/register?returnUrl=%2Fdashboard")
driver.find_element_by_id("Name").send_keys("Manish")
