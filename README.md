# Operacja-na-liczbach-JavaScript
<img width="503" height="829" alt="{0DC9F73F-8A92-4D46-9622-B5FD7A1EB7B6}" src="https://github.com/user-attachments/assets/1a52460d-8f4b-48ae-9df0-f4cc294bc0b5" />
let input = prompt("Podaj liczbę całkowitą:");

let number = parseInt(input);

if (isNaN(number) || number.toString() !== input.trim()) {
    console.log("To nie jest poprawna liczba całkowita");
} else {
    console.log(number);
    console.log(-number);
    console.log(number + 15);
    console.log(number + 0.5);
    console.log(number * number);
    console.log(number / 2);
    console.log(number % 2);
    console.log(number + 1);
    console.log(number - 1);
    console.log(Math.floor(number / 3));
    console.log(Math.ceil(number / 3));
    console.log(Math.round(number / 3));
    console.log(Math.sqrt(number));
    let random = Math.random() * 50;
    console.log(number * random);
    console.log(Math.abs(number));
}
