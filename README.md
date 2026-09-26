# Nomadic Traveler

Digital Nomad community and travel service platform for **nomadictraveler.org**.

## Project
- GitHub: `nomadictraveler-digital/nomadictraveler`
- Visibility: Public
- Contact: info@nomadictraveler.org
- Phone: +8809696505456

## MVP
- User registration/login and traveller profile
- FREE / EXPLORER / PREMIUM / VIP membership
- Global visa information and visa-service applications
- Secure visa document upload
- Manual hotel requests
- Manual flight requests
- Community posts, photo/video, comments, likes, shares
- Groups, country communities, Travel Buddy, Events/Meetups
- Private messaging foundation
- Staff roles and assignments
- Manual payment records and invoices
- Notifications and audit trail

## Suggested stack
Laravel 12 / PHP 8.3+, MySQL, Bootstrap 5/AdminLTE, Sanctum, Redis queues, object storage.

## Local setup
1. `composer install`
2. `cp .env.example .env`
3. Configure MySQL in `.env`
4. `php artisan key:generate`
5. `php artisan migrate --seed`
6. `php artisan storage:link`
7. `php artisan serve`

This repository is a production-oriented starter blueprint. Authentication, authorization, validation, media processing, payment gateways and supplier APIs should be completed and security-tested before production use.
