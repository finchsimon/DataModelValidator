# DataModelValidator
Library to Simplify Data Validation 

**Description**: 
DataModelValidator is a C# library designed to simplify data validation for .NET applications by providing a flexible and extensible validation framework. It enables developers to define validation rules for data models using a fluent API or attributes, validate data objects against these rules, and handle validation errors efficiently.

**Features**:

1. **Fluent Validation API**: Define validation rules using a fluent API, allowing for expressive and readable validation code.
2.  **Attribute-Based Validation**: Support validation using data annotations attributes, enabling developers to define validation rules directly within the data model classes.
5. **Built-In Validators**: Includes a set of built-in validators for common validation scenarios such as required fields, string length, numerical range, regular expression, and custom validation logic.
6. **Composite Validators**: Allow combining multiple validators into composite validators to handle complex validation scenarios.
7. **Asynchronous Validation**: Support asynchronous validation methods for scenarios requiring asynchronous data validation, such as database or web service calls.
8. **Error Handling**: Provide robust error handling mechanisms for handling validation errors, including customizable error messages, error codes, and error severity levels.
9. **Integration with ASP.NET Core**: Integrate seamlessly with ASP.NET Core framework for validating request models, view models, and DTOs in web applications.
10. **Extensibility**: Allow extending the validation framework with custom validators, custom error handling strategies, and integration with third-party validation libraries.

**Target Audience**:

- .NET developers building web applications, APIs, or services who need a reliable and easy-to-use data validation solution.
  
- Library authors who want to provide built-in validation support for their data models or APIs.
  
- Enterprises looking to enforce data validation standards across their .NET projects and ensure data integrity and consistency.

**Potential Use Cases**:

- Validating user input in web forms, API requests, or command-line applications to ensure data integrity and prevent security vulnerabilities such as SQL injection or cross-site scripting (XSS).
  
- Validating domain entities and business objects in domain-driven design (DDD) architectures to enforce business rules and constraints.
  
- Integrating with ORM frameworks such as Entity Framework Core to automatically validate database entities before saving changes to the database.
  
- Providing validation feedback to users in real-time during form submission or data entry workflows to improve user experience and reduce errors.

This library addressrs the need for a comprehensive and flexible data validation library in the .NET ecosystem, empowering developers to build robust and reliable applications with minimal effort and complexity.
