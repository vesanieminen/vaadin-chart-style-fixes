# Chart style fix

This repo demonstrates a Chart issue wrt. styling in the dark mode. The range selector zoom text is using a dark color when the dark mode is set:

<img width="274" alt="Screenshot 2022-11-15 at 14 35 28" src="https://user-images.githubusercontent.com/108755/201921965-30bbe71c-9ff2-4b8e-8d76-f20b8a7ff6e1.png">

Steps to reproduce:
1. Run the app (instructions below)
2. Set the OS theme to dark mode
3. Navigate to http://localhost:8080
4. See that the zoom text has a dark color. 

## Running the application

The project is a standard Maven project. To run it from the command line,
type `mvnw` (Windows), or `./mvnw` (Mac & Linux), then open
http://localhost:8080 in your browser.
