# Student’s Group Study Software

It is a simple web application where developers can create groups and ask questions or provide solutions to other students

## Technologies

- Django
- Python
- HTML
- CSS
- JavaScript

## Getting Started

To get a local copy up and running follow these simple steps:

### Installation

1. Create a local copy of this git repository with `git clone` command.

   ```shell
   $ git clone https://github.com/dhavall13/CRM-System.git
   ```

2. Create a Virtual Enviornment with the `virtualenv` module.

   ```shell
   $ virtualenv .
   ```

3. Once you’ve created a virtual environment, you may activate it.

   ```shell
   $ source scripts/activate
   ```

4. Now, install the requirements from the `requirements.txt` file.

   ```shell
   $ pip install -r requirements.txt
   ```

5. Now, apply the migrations with the management command.

   ```shell
   $ python manage.py migrate
   ```

6. Finally, start the developement server with the management commnad.

   ```shell
   $ python manage.py runserver
   ```

## Authors

- Dhaval Chaudhari - [dhavall13](https://github.com/dhavall13/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](../main/LICENSE) file for details
