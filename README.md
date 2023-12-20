## Laravel-Multi-Tenant

A complete example of a multi-tenant Laravel application. It is only a demo, not a real application to use for production.

### What is Multi Tenant SaaS?

Multi-tenant SaaS, or Software as a Service, refers to a type of software architecture where a single instance of the software application serves multiple customers, known as tenants. Each tenant shares the same underlying infrastructure and code base, but their data and configurations are kept separate and isolated from one another.

## Technology Usage

-   **[Laravel 10](https://laravel.com/docs/10.x)**
-   **[Blade Template](https://laravel.com/docs/10.x/blade#main-content)**
-   **[Vite JS](https://vitejs.dev/)**
-   **[Tailwind CSS](https://tailwindcss.com/)**
-   **[Tenancy for Laravel](https://tenancyforlaravel.com/)**
-   **[Laravel Permission](https://spatie.be/docs/laravel-permission/v6)**

## How to Run

Open your favourite terminal of and follow the instructions below to run the complete project on your machine!

### Step 1:

Clone the github repository by running the following command

```
git clone https://github.com/tarikulwebx/Laravel-Multi-Tenant.git
```

Navigate to the project directory

```
cd Laravel-Multi-Tenant
```

### Step 2:

Clone **.env.example** file and save as **.env**. Change environment variables as your need.

### Step 3:

Run following command to generate app key.

```
php artisan key:generate
```

### Step 4

Migrate and seed by running the command

```
php artisan migrate --seed
```

### Step 5

Run the project

```
php artisan serve
```

Open the project on http://localhost:8000/ link and tenants directory will be like the http://<tenant_domain_name>.localhost:8000/

## Thank You!

Be sure to give me a star on this project.
