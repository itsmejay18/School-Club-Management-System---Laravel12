# School Club Management System

This Laravel project manages club activities, attendance, member participation, and admin-level coordination for a school organization workflow.

## Core Modules

- Admin and member dashboards
- Activity management
- Attendance tracking
- Member and user management
- Authentication and approval-gated access

## Tech Stack

- Laravel and PHP
- Blade templates
- Eloquent models for activities, attendance, and users
- Database configured through `.env`
- Node tooling for frontend assets

## Project Structure

- `app/Http/Controllers` contains admin and member activity, attendance, dashboard, and user-management logic
- `app/Models` includes `Activity`, `Attendance`, and `User`
- `resources/views` contains dashboard, auth, activity, attendance, and member-management pages
- `routes/web.php` defines protected role-based flows

## Getting Started

1. Install PHP, Composer, Node.js, and a database server.
2. Run `composer install`.
3. Create a `.env` file from `.env.example`.
4. Configure the database settings in `.env`.
5. Run `php artisan key:generate`.
6. Run `php artisan migrate`.
7. Run `npm install`.
8. Run `npm run dev`.
9. Start the application with `php artisan serve`.

## Notes

- The route file indicates approval-aware access control, so make sure test accounts reflect the expected roles and approval states.
