# SampleSelProject

This project demonstrates Selenium WebDriver automation in Java.

## What it does
- Launches 'www.google.com'
- Enters 'learn python' in the search box

## How to run
1. Ensure you have Chrome and chromedriver installed.
2. Build the project with Maven:
   ```powershell
   mvn clean compile
   ```
3. Run the test:
   ```powershell
   mvn exec:java -Dexec.mainClass="com.example.GoogleSearchTest"
   ```

## Notes
- You may need to set the path to chromedriver in `GoogleSearchTest.java` if it's not in your system PATH.
