# Stefan Zayats

## Contacts

* **Phone:** +375 29 531 28 40
* **E-mail:** stepanzayac@gmail.com
* **Location:** Minsk, Belarus
* **GitHub:** stefan-zayats

## About Me

I am 26 years old, I work as an engineer for automated control systems. My current job inspires me less than programming. I want to get more knowledge and skills that will be enough to become a front-end developer.

## Skills
* FBD
* LAD
* HTML
* JavaScript (Basic)
* Git

## Code Example

```
function revrot(str, sz) {

	let arr = [];

	if (sz <= 0 || str == 0 || sz > str.length) {
		console.log(`""`);
	} else {
		for (let j = 0; j < str.length; j += sz) {
			arr.push(str.substr(j, sz));
		}
	}

	function sumOfCubes(s) {
		let sum = 0;
		for (let i = 0; i < s.length; i++) {
			sum += Math.pow(s[i], 3);
		}
		return sum;
	}

	function newStr(n) {
		if (sumOfCubes(n) % 2 > 0) {
			n = n.substr(1, n.length - 1) + n[0];
		} else {
			n = n.split("").reverse().join("");
		}
		return n;
	}

	let sumNewStr = "";
	for (let a = 0; a < arr.length; a++) {
		if (arr[a].length < sz) {
			break;
		}
		sumNewStr += newStr(arr[a]);
	}
	return sumNewStr;
}
```
## Education

Belarusian State University of Informatics and Radioelectronics

## Languages
* Russian
* English - A2