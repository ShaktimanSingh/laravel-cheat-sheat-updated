
# 📘 Laravel Artisan Command Cheat Sheet

## 🧰 General Commands

```bash
php artisan list             # List all available Artisan commands
php artisan help             # Display help for a command
php artisan version          # Display the Laravel version
php artisan inspire          # Display an inspiring quote
php artisan tinker           # Interact with your application
php artisan serve            # Serve the application on the PHP development server
php artisan env              # Display the current framework environment
php artisan down             # Put the application into maintenance mode
php artisan up               # Bring the application out of maintenance mode
php artisan config:cache     # Create a cache file for faster configuration loading
php artisan config:clear     # Remove the configuration cache file
php artisan route:cache      # Create a route cache file for faster route registration
php artisan route:clear      # Remove the route cache file
php artisan view:cache       # Compile all of the application's Blade templates
php artisan view:clear       # Clear all compiled view files
php artisan cache:clear      # Flush the application cache
php artisan optimize         # Cache the framework bootstrap files
php artisan key:generate     # Set the application key
```

## 🗃️ Database Commands

```bash
php artisan migrate                  # Run the database migrations
php artisan migrate:rollback         # Rollback the last database migration
php artisan migrate:reset            # Rollback all database migrations
php artisan migrate:refresh          # Reset and re-run all migrations
php artisan migrate:fresh            # Drop all tables and re-run all migrations
php artisan db:seed                  # Seed the database with records
php artisan db:wipe                  # Drop all tables, views, and types
php artisan schema:dump              # Dump the current database schema
php artisan schema:restore           # Restore the database schema from a dump
```

## 🛠️ Make Commands

```bash
php artisan make:model ModelName                 # Create a new Eloquent model class
php artisan make:controller ControllerName       # Create a new controller class
php artisan make:migration create_table_name     # Create a new migration file
php artisan make:seeder SeederName               # Create a new seeder class
php artisan make:factory FactoryName             # Create a new model factory
php artisan make:middleware MiddlewareName       # Create a new middleware class
php artisan make:request RequestName             # Create a new form request class
php artisan make:resource ResourceName           # Create a new resource
php artisan make:policy PolicyName               # Create a new policy class
php artisan make:command CommandName             # Create a new Artisan command
php artisan make:event EventName                 # Create a new event class
php artisan make:listener ListenerName           # Create a new event listener class
php artisan make:job JobName                     # Create a new job class
php artisan make:mail MailName                   # Create a new email class
php artisan make:notification NotificationName   # Create a new notification class
php artisan make:provider ProviderName           # Create a new service provider class
php artisan make:rule RuleName                   # Create a new validation rule
php artisan make:test TestName                   # Create a new test class
php artisan make:channel ChannelName             # Create a new channel class
php artisan make:observer ObserverName           # Create a new observer class
php artisan make:resource ResourceName           # Create a new resource
```

## 🔐 Authentication & Authorization

```bash
php artisan make:auth              # Scaffold basic login and registration views and routes
php artisan make:policy PolicyName # Create a new policy class
php artisan make:middleware Name   # Create a new middleware class
```

## 🧪 Testing

```bash
php artisan test                   # Run the application tests
php artisan test --filter=TestName # Run tests that match the given filter
php artisan dusk                   # Run the Dusk tests
php artisan make:test TestName     # Create a new test class
php artisan make:factory Name      # Create a new model factory
```

## 🚀 Deployment & Optimization

```bash
php artisan deploy                 # Deploy the application
php artisan env:set APP_ENV=prod   # Set the application environment
php artisan optimize               # Cache the framework bootstrap files
php artisan config:cache           # Create a cache file for faster configuration loading
php artisan route:cache            # Create a route cache file for faster route registration
php artisan view:cache             # Compile all of the application's Blade templates
```

## 📦 Package Management

```bash
php artisan package:discover       # Rebuild the cached package manifest
php artisan vendor:publish         # Publish any publishable assets from vendor packages
```

## 🧹 Maintenance Mode

```bash
php artisan down                   # Put the application into maintenance mode
php artisan up                     # Bring the application out of maintenance mode
```

## 🧰 Miscellaneous

```bash
php artisan schedule:run           # Run the scheduled commands
php artisan queue:work             # Start processing jobs on the queue
php artisan queue:restart          # Restart queue workers
php artisan queue:listen           # Listen to a given queue
php artisan event:generate         # Generate the missing events and listeners based on registration
```

---

**Note**: Some commands like `php artisan make:auth` have been removed in Laravel 6 and later. For authentication scaffolding in newer versions, consider using Laravel Breeze, Jetstream, or Fortify.

For a complete list of Artisan commands and their options, refer to the official Laravel documentation: [Artisan Console - Laravel](https://laravel.com/docs/artisan)
