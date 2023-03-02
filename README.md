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

## Usage


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

![Video1](./video/video1.mov)

![Video1](./video/video2.mov)


https://user-images.githubusercontent.com/116671695/222326101-06959fe9-ac8d-4cdc-a6e2-fb2b4615047f.mov



## Contributors

DU Starter Code
Terrence McCoy


---

## License

MIT
