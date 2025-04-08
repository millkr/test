let num1 = parseFloat(prompt("Введите первое число:"));
let num2 = parseFloat(prompt("Введите второе число:"));
if (isNaN(num1) || isNaN(num2)) {
alert("Пожалуйста, введите числа!");
} else {
let sum = num1 + num2;
console.log("Сумма:", sum);
let resultElement = document.createElement("p");
resultElement.textContent = "Сумма: " + sum;
document.body.appendChild(resultElement);
}

