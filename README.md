Sure, here's an updated version of the README file that includes the pull request format and the updated project name:

# 15min

15min is an open source video conferencing app designed to encourage short and productive meetings. The app allows users to create meetings that are limited to 15 minutes, ensuring that discussions stay focused and on track.

## Project Description

15min is an open source video conferencing app designed to encourage short and productive meetings. The app allows users to create meetings that are limited to 15 minutes, ensuring that discussions stay focused and on track.

The frontend of the app is built with Next.js and TypeScript, using Tailwind CSS for styling. The backend is built with Django and Django REST Framework, with a focus on performance and scalability.

The app features a simple and intuitive interface, making it easy for users to create and join meetings. Meeting links can be shared with participants via email or instant message, and the app also includes a built-in chat feature for quick communication during meetings.

15min is ideal for teams and individuals who want to increase productivity and efficiency in their meetings, without sacrificing collaboration and communication. The app is fully customizable and extensible, making it easy to add new features and functionality as needed.

## Style Guides

For guidelines on front-end and back-end development, please see the following README files:

- [Front-end Style Guide](frontend/STYLE_GUIDE.md)
- [Back-end Style Guide](backend/STYLE_GUIDE.md)

## Getting Started

To get started with 15min, follow these steps:

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/15min.git
```

2. Install the dependencies for the frontend and backend:

```
cd 15min
cd frontend && npm install
cd ..
cd backend && pip install -r requirements.txt
```

3. Start the frontend and backend servers:

```
cd frontend && npm run dev
cd ..
cd backend && python manage.py runserver
```

4. Visit [http://localhost:3000](http://localhost:3000) to use the app.

## Contributing

We welcome contributions to 15min! To contribute, follow these steps:

1. Fork the repository to your GitHub account.

2. Clone the forked repository to your local machine:

```
git clone https://github.com/your-username/15min.git
```

3. Create a new branch for your changes:

```
git checkout -b my-feature-branch
```

4. Make your changes and commit them:

```
git add .
git commit -m "Added my feature"
```

5. Push your changes to your forked repository:

```
git push origin my-feature-branch
```

6. Create a pull request on the main repository to merge your changes. Please follow this format for your pull request title:

```
[<type>] <description>
```

Where `<type>` is one of the following:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation changes
- **style**: Changes to code style or formatting
- **refactor**: Code refactoring
- **test**: Changes to tests
- **chore**: Other changes (e.g. build, CI/CD)

And `<description>` is a description of your changes that should include:
 - the issue you are tackling.
 - the task you completed.
 - how you completed them.
 - for changes in the ui you should include screenshots.

## License

15min is released under the [MIT License](LICENSE).
