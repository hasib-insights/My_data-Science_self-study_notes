## F-Strings  
To specify a string as an f-string, simply put an f in front of the string literal, and add curly brackets {} as placeholders for variables and other operations.
```python
price = 59
txt = f"The price is {price} dollars"
print(txt)
```
output:
```
The price is 59 dollars
```
Display the price with 2 decimals:
```python
price = 59
txt = f"The price is {price:.2f} dollars"
print(txt)
```
output:
```
The price is 59.00 dollars

```
