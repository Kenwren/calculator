<h1>Calculator app</h1>

This is a straightforward JavaScript, HTML, and CSS calculator application for the web. Along with basic mathematical operations, it has an easy-to-use interface.


<h2>Table of Contents</h2>


1. Features
2. Demo
3. Prerequisites
4. Installation
5. Usage
6. Customization



<h2>Features</h2>

1. Operations including addition, subtraction, multiplication, and division.
2. Functions can be deleted (DE) or cleared (AC).
3. adaptable design for a range of platforms.
4. serves as any basic calculators.


<h2>DEMO</h2>

You can try out the calculator [here](https://kenwren.github.io/calculator/).


<h2>Prerequisites</h2>

Web browser (such as Chrome, Firefox, Edge (Windows), or Safari(Apple)) is required.


<h2>Installation</h2>

1. Make a clone of the repository:
   
use ```backicks``` with the name of the language

```bash
git clone https://github.com/your-username/calculator.git
```

2. Slide open the project folder:

use ```backicks``` with the name of the language

```bash
cd calculator
```

3. Launch the index.html file in the web browser of your choice.


<h2>Application</h2>

1. Navigate to the index.html file in the browser.
2. Enter numbers by using the numeric buttons.
3. For arithmetic operations, use the operator buttons (+, -, *, /).
4. The "AC" button can be used to clear the screen.
5. To remove the final digit, press the "DE" button.
6. To determine the outcome, click the "=" button.



<h2>Customization</h2>


The styles in the index.css file can be changed to alter the calculator's appearance. Please feel free to experiment with different fonts, colors, and sizes to suit your tastes.
```css
.calculator {
  background: #555;
  color: #fff;
}
```

The JavaScript in the script.js file can be used to add the function of the calculator's buttons (=), (AC), (DEL) in order to execute the action.
```JavaScript
arr.forEach(button => {
    button.addEventListener('click', (e) =>{
        if(e.target.innerHTML == '='){
            string = eval(string);
            input.value = string;
        }

        else if(e.target.innerHTML == 'AC'){
            string = "";
            input.value = string;
        }
        else if(e.target.innerHTML == 'DEL'){
            string = string.substring(0, string.length-1);
            input.value = string;
        }
        else{
            string += e.target.innerHTML;
            input.value = string;
        }
```
