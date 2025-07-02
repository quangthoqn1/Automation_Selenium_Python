# Cài đặt Selenium và Allure
pip install selenium
pip install allure-pytest


# Chạy test + sinh báo cáo
pytest --alluredir=allure-results
allure generate allure-results -o allure-report --clean
