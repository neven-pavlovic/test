# test
Test Assignment

All tests were run on Windows 10, 64-bit, using Google Chrome, version: 86.0.4240.183

How to run and review code:

1. Download Python from https://www.python.org/downloads/ and install it.
2. Download PyCharm Community version from https://www.jetbrains.com/pycharm/download/#section=windows
3. Download the code as ZIP file and unzip it
4. Open the project in PyCharm by opening PyCharm, clicking on File -> Open and than navigating to the test-master folder, selecting it and clicking OK buton
5. Press Ctrl+Alt+S to open the project Settings/Preferences.
6. In the Settings/Preferences dialog, select Project: test-master, and then Python Interpreter
7. Click the little gears icon on top-right and than click Add
8. Choose the interpreter System interpreter, then find the path to your Python executable (for me it's: C:\Users\Admin\AppData\Local\Programs\Python\Python39\python.exe)
9. Click OK, than OK.
10. You will now see list of packages. Click + sign bellow gears icon and search for selenium. When you find it, select it and click Install Package. Wait until the install is complete.
11. Close the settings.
12. Download chromedriver.exe from https://chromedriver.storage.googleapis.com/index.html?path=86.0.4240.22/ and save it to C:\\Drivers\chromedriver.exe
13. In PyCharm, navigate to Test Suites/AllTests/alltests.py and double-click it.
14. Choose which tests you want to run by changing the code. Explanation of how to do that is given in the comments.
15. Right click on alltests.py in Project window and click Run 'alltests'

A little bit more explaining:

If you want to run only one test, do this:
1. For Cheese test: Navigate to Package_Cheese/tests/test_cheese.py in PyCharm Project window, right click that file and click Run 'Unittests for test_ch..."
2. For DemoQA test: Navigate to Package_DemoQA/tests/test_demoqa.py in PyCharm Project window, right click that file and click Run 'Unittests for test_de..."
3. For OrangeHRM test: Navigate to Package_OrangeHRM/tests/test_orangehrm.py in PyCharm Project window, right click that file and click Run 'Unittests for test_or..."
  
If you have any questions, feel free to contact me!
