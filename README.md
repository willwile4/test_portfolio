# test_portfolio

## Objectives
1. To become more familiar with automation using Selenium
2. To make sure my portfolio page performs correctly through various browers.
3. To learn and see how I can better write web apps for tests in the future

## Tools
1. Selenium
2. Unittest

## How to Run
Set Virtual Environment
```
$ echo layout python3 > .envrc && direnv allow
```
Install requirements
```
$ pip install -r requirements.txt
```
Run Tests
```
$ python3 portfolio_test.py
```

### Testing Plan
* Test each browser type, Chrome, Firefox, Safari, IE, Opera, Android, iOS
* In each browser, test:
  - title
  - correct link text for desktop
  - correct link css image class for small screen/mobile
  - correct link address
  - each portfolio piece has buttons for its live demo, github, and external
  sources(optional)

#### Later additions
1. Test each live demo

#### Author
[Will Warren](https://willwile4.github.io)
