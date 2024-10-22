Travel Agency management system made as a project on our college's final year. The goal was to build a full-stack web application that enables agency employees to perform CRUD operations with offers provided by agency itself, and application guests to reserve a trip for any offer that is available. Application is built with Laravel, React and Tailwind CSS, and also has Dockerfiles provided in Docker branch. 

### Installation and Build

1. Download source code from this branch and extract it somewhere on your machine.
2. Start Apache and MySQL ports in your WAMP/XAMPP Control Panel.
3. Enter command prompt, change directory to the project path (cd /project_path).
4. Run 'php artisan migrate:fresh --seed' command, wait for the data to generate.
5. Run 'php artisan serve' command.
6. Enter another command prompt, change directory to the frontend folder of this project (cd /project_path/frontend).
7. Run 'npm run dev' command.
8. Open displayed address, after Local:

## Process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- [Laravel](https://laravel.com/docs/9.x/installation) - PHP Framework 
- [React](https://reactjs.org/) - JS library
- [Tailwind CSS](https://v2.tailwindcss.com/docs) - Utility-first CSS Framework 
- [Docker](https://docs.docker.com) - Containerization platform 
- [React Toastify](https://npmjs.com/package/react-toastify)

### Useful resources

- [React + Laravel Full Stack application](https://www.youtube.com/watch?v=qJq9ZMB2Was) - This helped us for the crucial part of the project: integrating Laravel on the backend with React on the frontend.
- [Dockerize Laravel-Vite and React app](https://betterprogramming.pub/dockerize-laravel-vite-react-application-in-your-development-environment-a118aea4a02d) - This is an amazing article which helped us to better understand Dockerization process of Laravel-Vite and React applications. I'd recommend it to anyone still learning this concept.
