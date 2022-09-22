# React-Calculator
https://www.youtube.com/watch?v=DgRrrOt0Vr8 (Web Dev Simplified Tutorial)
Minified to three files.
Fixed the focus issue by removing ",.calculator-grid>button:focus" from the CSS
Fixed the decimal from breaking the code when clicked before a number by adding- 
"?" to "if (payload.digit==="."&&state.currentOperand?.includes(".")){return state}"
