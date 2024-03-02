<a name="topage"></a>

# 010_q&a

### [ question ]

* Write a program that prints the numbers from `1` to  `n`, 
* but for multiples of `3`, print `"Fizz"` instead of the number, 
* and for multiples of `5`, print `"Buzz"`. 
* For numbers which are multiples of both `3 and 5`, print `"FizzBuzz"`.


### [ solution ]

#### Js

```sh
function fnFizzBuzz() {

    var output = [];
    var count = 1;

    for (var i = 0; i < 16; i++) {
        if (((count % 3) == 0) && ((count % 5) == 0)) {
            output.push("fizzBuzz");
        }
        else if (count % 3 == 0) {
            output.push("fizz");
        }
        else if (count % 5 == 0) {
            output.push("buzz")
        }
        else {
            output.push(count);
        }
        count++;
    }
    
    return output;
}


let outputfnFizzBuzz = fnFizzBuzz();
console.log(outputfnFizzBuzz);
```

#### output
```sh
[1,2,"fizz",4,"buzz","fizz",7,8,"fizz","buzz",11,"fizz",13,14,"fizzBuzz",16]
```

-----

### [ Thoughts ]

  1. xxxx
  

<p align="right">(<a href="#topage">back to top</a>)</p>
<br/>
<br/>

Write a program that prints the numbers from `1` to  `n`, 
but for multiples of `3`, print `"Fizz"` instead of the number, 
and for multiples of `5`, print `"Buzz"`. 
For numbers which are multiples of both `3 and 5`, print `"FizzBuzz"`.
