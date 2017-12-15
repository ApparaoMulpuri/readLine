# readLine
Explains you how to use the **readLine** function in Swift.


1. #### Reading data from the Keyboard in Swift

```
let input = readLine()
if let input = input {
    print(input) //Input will be printed out
}
```

2. #### Reading Int from the keyboard

```
let input = Int(readLine()!)
if let input = input {
    print(input) //Input integer will be printed out.
}
```

3. #### Reading String from the keyboard

```
let input = String(readLine()!)
if let input = input {
    print(input) //Input Stirng will be printed out.
}
```

4. #### Reading data from the keyboard and convert that into an Array

```
let input = readLine()
if let input = input {
    let numbersFromKeyboard = input.split(separator: " ")
    let numbers = numbersFromKeyboard.map { Int(String($0))! }
    print(numbers)
}
```

