# AWS_bot
This is a Uses Amazon Web Services for Lex a bot builder and Lambda to fulfill requests reguarding retirement investing. 
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [AWS](https://github.com/aws) - Amazon Web Service github for help navigating the software

* [JSON](https://github.com/topics/json) - JSON (JavaScript Object Notation) is a standard file format that uses text to communicate data objects to array data types

* [AWS LEX](https://aws.amazon.com/lex/) - a fully managed artificial intelligence (AI) service with advanced natural language models to design, build, test, and deploy conversational interfaces in applications

* [AWS LAMBDA](https://aws.amazon.com/lambda/) - a serverless, event-driven compute service that lets you run code for virtually any type of application or backend service without provisioning or managing servers
---

## Installation Guide

Before running the application first install the following dependencies. Note that if you are running on the cloud and not locally you will have to run all lines of code.

```
You will need to set up an AWS account to run Lex and Lambda.
```


---

## Test

<img width="1162" alt="Screen Shot 2023-03-01 at 8 58 32 PM" src="https://user-images.githubusercontent.com/116671695/222328040-d6a651d3-8b33-4333-bdb5-89056c8e0b62.png">
<img width="1274" alt="Screen Shot 2023-03-01 at 8 59 00 PM" src="https://user-images.githubusercontent.com/116671695/222328051-e2c39db3-14c3-40eb-becb-8664e29acd79.png">
<img width="1311" alt="Screen Shot 2023-03-01 at 8 59 12 PM" src="https://user-images.githubusercontent.com/116671695/222328064-c7eded04-ff4c-4431-b67c-eecbe0ded8e4.png">
<img width="1227" alt="Screen Shot 2023-03-01 at 8 59 22 PM" src="https://user-images.githubusercontent.com/116671695/222328075-f8410376-2a53-4297-9f1c-da83de5ccea1.png">

---

## Examples
```
 if age is not None:
        age = parse_int(age)
        if age > 64:
            return build_validation_result(
                False,
                "age",
                "You should be under the age of 65 to use this service, "
                "please provide a different age.",
            )
```

---

## Videos


https://user-images.githubusercontent.com/116671695/222326209-ae0ea6a7-2556-4f31-9ed9-fcd382ee54f4.mov





https://user-images.githubusercontent.com/116671695/222326333-b6b41b77-a389-41a4-b1bf-e57876168e6c.mov




## Contributors

DU Starter Code
Terrence McCoy


---

## License

MIT
